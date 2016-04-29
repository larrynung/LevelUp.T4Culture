# LevelUp.T4Culture
Generate culture helper class to use culture without hardcode  

Step  
1. Add LevelUp.T4Culture from nuget  
2. Run T4 template to generate helper class  
3. Use culture with helper class

    ...
    var currentThread = Thread.CurrentThread;
    currentThread.CurrentCulture = CultureInfo.GetCultureInfo(CultureNames.ZH_TW);
    ...

Link
----
* [T4 template - CultureNames.tt - Level Up](http://larrynung.github.io/2016/03/08/t4-template-culturenames-dot-tt/)
* [NuGet Gallery | LevelUp.T4Culture](https://www.nuget.org/packages/LevelUp.T4Culture/)
