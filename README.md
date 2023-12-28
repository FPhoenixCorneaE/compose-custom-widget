# compose-custom-widget

## compose版自定义小部件

[![latest](https://jitpack.io/v/FPhoenixCorneaE/compose-custom-widget.svg)](https://jitpack.io/#FPhoenixCorneaE/compose-custom-widget)

```groovy
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        mavenCentral()
        maven { url 'https://jitpack.io' }
    }
}
```

```groovy
dependencies {
    implementation 'com.github.FPhoenixCorneaE:compose-custom-widget:latest'
}
```

### 更新日志

#### 2023-12-28 
* 添加自定义跑马灯光圈[MarqueeAperture](https://github.com/FPhoenixCorneaE/compose-custom-widget/blob/main/custom-widget/src/main/java/com/fphoenixcorneae/widget/MarqueeAperture.kt)
<br>
致谢：[android 自定义view 跑马灯-光圈效果](https://juejin.cn/post/7171030095866363934)

#### 2023-12-27 
* 添加自定义随机滚动小球布局[RandomlyRollBallLayout](https://github.com/FPhoenixCorneaE/compose-custom-widget/blob/main/custom-widget/src/main/java/com/fphoenixcorneae/widget/RandomlyRollBallLayout.kt)
* 添加自定义系统ui脚手架，适配状态栏、底部导航栏[SystemUiScaffold](https://github.com/FPhoenixCorneaE/compose-custom-widget/blob/main/custom-widget/src/main/java/com/fphoenixcorneae/widget/SystemUiScaffold.kt)
* 添加自定义选项卡[TabRow](https://github.com/FPhoenixCorneaE/compose-custom-widget/blob/main/custom-widget/src/main/java/com/fphoenixcorneae/widget/TabRow.kt)

#### 2023-12-26 
* 添加自定义输入框[CustomEditText](https://github.com/FPhoenixCorneaE/compose-custom-widget/blob/main/custom-widget/src/main/java/com/fphoenixcorneae/widget/CustomEditText.kt)
* 添加自定义正方形布局[Square](https://github.com/FPhoenixCorneaE/compose-custom-widget/blob/main/custom-widget/src/main/java/com/fphoenixcorneae/widget/Square.kt)
* 添加自定义垂直分割线[VerticalDivider](https://github.com/FPhoenixCorneaE/compose-custom-widget/blob/main/custom-widget/src/main/java/com/fphoenixcorneae/widget/VerticalDivider.kt)
* 添加自定义打字机效果Text[TypewriterText](https://github.com/FPhoenixCorneaE/compose-custom-widget/blob/main/custom-widget/src/main/java/com/fphoenixcorneae/widget/TypewriterText.kt)
* 添加自定义三角形[Triangle](https://github.com/FPhoenixCorneaE/compose-custom-widget/blob/main/custom-widget/src/main/java/com/fphoenixcorneae/widget/Triangle.kt)
* 添加自定义开关[Switch](https://github.com/FPhoenixCorneaE/compose-custom-widget/blob/main/custom-widget/src/main/java/com/fphoenixcorneae/widget/Switch.kt)
<br>
致谢：[Compose制作一个“IOS”效果的SwitchButton](https://juejin.cn/post/7134702107742961701)