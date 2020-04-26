由于原库作者okhttp-OkGo很久没更新核心库okhttp3,RxJava,RxJava2,所以fork下来，花了点时间更新了一下核心库，迁移到了AndroidX，添加了AndroidX的混淆规则

去掉对RxJava1的支持，保留RxJava2

其余的没有做变动，包括代码中的作者信息什么的，因为没必要，目的仅仅是为了更新核心库。

## 原库okhttp-OkGo地址
 * [https://github.com/jeasonlzy/okhttp-OkGo](https://github.com/jeasonlzy/okhttp-OkGo) 
 
使用方式：

项目根目录gradle
```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```
app下的gradle
```
implementation 'com.github.Alvin9234:OkGo:v1.0'

```
 
 
