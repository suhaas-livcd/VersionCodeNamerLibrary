<img src="https://suhaas-livcd.github.io/screenShots/ReadMeVersionCodeNamer.png" align="center" title="example use of library" width="818" height="415">

[![](https://jitpack.io/v/suhaas-livcd/VersionCodeNamerLibrary.svg)](https://jitpack.io/#suhaas-livcd/VersionCodeNamerLibrary)

## What is it ?
>VersionCodeNamer is a library to deal automatic naming of the versions in a systematic and organised way with the version names.
- Have you ever wondered what should be the next **Version name** of your app release ?
- Should it be my favourite desert **Pastel de nata**, a large glacier **vatnajökull** or **foo** whatever something.
- Then well you are at the right place.
- You dont have to worry about the names, as we have predefined list of different categories.

### Installation

Use the [jitpack.io](https://jitpack.io/#suhaas-livcd/VersionCodeNamerLibrary) to check dependency.

```
implementation 'com.github.suhaas-livcd:VersionCodeNamerLibrary:1.0.1'
```

### Usage

```
    ...
    import com.hosteloha.versioncodenamerlib.VersionCodeNamer;
    import com.hosteloha.versioncodenamerlib.VersioningType;
    ...
    String customVersionName = VersionCodeNamer.getName(versionCode, VersioningType.CHEMICAL_ELEMENTS);
    TextView appVersionName = findViewById(R.id.application_version_name);
    appVersionName.setText(customVersionName);
    ...
```


     
### Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. Please make sure to update tests as appropriate.

----

### changelog
* Dec 27, 2019 - **A kindle**

---- 
### thanks
* [Alphabetizer](https://alphabetizer.flap.tv/lists/)


### License
[MIT](https://choosealicense.com/licenses/mit/)
