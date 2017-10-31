# Building Reactive Finance App

Lets start the journey by starting a new project, we will use the new shiny Kotlin, of course RxAndroid and for the UI elemnts we will use library called RxBinding.

1. Open new project in the Android Studio and create new project
2. select **Include Kotlin Support \( **because we use Kotlin language we don't need to install Retrolamda\)
3. before we start coding we need to add all the **Dependencies**
   ![](/assets/Screen Shot 2017-10-31 at 10.41.46.png)

cool! lets worm up, and create new package and name it: model, then create new Kotlin class called stock.

```
data class Stock(val symbol: String, val price : BigDecimal, val date : Date)
```

> when adding data the compiler will auto generate `equals(), hashCode(), toString() copy`



 



