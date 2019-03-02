# SDCardTest

Android6.0访问外置SD卡受限

通过修改framework部分，添加`android.permission.WRITE_MEDIA_STORAGE`权限

只要app申请这个权限就直接给

这样app就能像4.4之前一样操作外置SD卡