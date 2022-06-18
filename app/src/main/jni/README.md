invoke-static {p0}, Lnet/shayne/mod/menu/Main;->Start(Landroid/content/Context;)V

invoke-static {p0}, Lnet/shayne/mod/menu/Main;->StartWithoutPermission(Landroid/content/Context;)V

<uses-permission android:name="android.permission.SYSTEM_ALERT_WINDOW"/>

<service android:name="net.shayne.mod.menu.Launcher" android:enabled="true" android:exported="false" android:stopWithTask="true" />
