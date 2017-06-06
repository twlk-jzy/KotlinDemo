# KotlinDemo


1、在项目中build.gradle中dependencies 添加

  classpath "org.jetbrains.kotlin:kotlin-gradle-plugin:$kotlin_version"
  
2、在app下中build.gradle中天健插件


  apply plugin: 'kotlin-android'
  apply plugin: 'kotlin-android-extensions'
  
3、在MainActivity中导入 
  import kotlinx.android.synthetic.main.activity_main.*
  
