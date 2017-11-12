# DeezFoodz
Ray Wendelich Dagger Tutorial

Link: https://www.raywenderlich.com/146804/dependency-injection-dagger-2

# Generic steps for code injection
1. Add inject() in AppComponent with Target class argument.
2. Add @Provides annotated method in the Module class for each source object to be injected.
3. Add @Inject annotation to each Source member variable in Target class.
4. Add MyApplication.getAppComponent().inject(this) in OnCreate() in Target class.