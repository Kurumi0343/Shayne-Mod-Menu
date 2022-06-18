# with overlay permission
invoke-static {p0}, Lnet/shayne/mod/menu/Main;->Start(Landroid/content/Context;)V
# without overlay permission
invoke-static {p0}, Lnet/shayne/mod/menu/Main;->StartWithoutPermission(Landroid/content/Context;)V
# overlay permission
<uses-permission android:name="android.permission.SYSTEM_ALERT_WINDOW"/>
# floating launcher permission
<service android:name="net.shayne.mod.menu.Launcher" android:enabled="true" android:exported="false" android:stopWithTask="true" />
