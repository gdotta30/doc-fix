# Programming a functionality provided by a native Super App

## Setting

- Point the local repository URL at [build.gradle:23](https://github.com/genexus-colab/gx-super-app/blob/main/Android/MiniAppCaller/build.gradle#L23) to the directory where it is located.

## HowTo: Call a Super App API from a Mini App

To implement a communication interface between Mini Apps and Super Apps, visit the official documentation:

- For a Native mobile Mini App, please refer to: [HowTo: Call a Super App API from a Native mobile Mini App](https://wiki.genexus.com/commwiki/wiki?58185,HowTo%3A+Call+a+Super+App+API+from+a+Native+mobile+Mini+App#HowTo%3A+Call+a+non-GeneXus+Super+App+API)
- For a Web Mini App, please refer to: [HowTo: Call a Super App API from a Web Mini App](https://wiki.genexus.com/commwiki/wiki?57430,HowTo%3A+Call+a+Super+App+API+from+a+Web+Mini+App)

- For a Native mobile Mini App, please refer to: [HowTo: Call a Super App API from a Native mobile Mini App](https://wiki.genexus.com/commwiki/wiki?58185,HowTo%3A+Call+a+Super+App+API+from+a+Native+mobile+Mini+App#HowTo%3A+Call+a+non-GeneXus+Super+App+API)
- For a Web Mini App, please refer to: [HowTo: Call a Super App API from a Web Mini App](https://wiki.genexus.com/commwiki/wiki?57430,HowTo%3A+Call+a+Super+App+API+from+a+Web+Mini+App)

## Conclusion

Once the "Skeleton" of the ExternalApi is built, the iteration is reduced to creating new methods with the GeneXus External Object and their respective IMethodInvokers (or IMethodInvokerWithActivityResult) in the native implementation and then "registering" them through ExternalApi.addMethodHandler.
