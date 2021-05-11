# Opencore-update
Opencore升级简版教程

 1.  打开网址：[https://github.com/acidanthera/OpenCorePkg/releases]()
 2. 下载opencore新版本，解压，将x64文件夹拖出来，其余删除；
 3. 打开网址：[https://github.com/acidanthera/OcBinaryData]()，解压，将Resources替换进旧版本同类项；
 4. 将新版x64文件夹展开，将EFI目录下BOOT和OpenCore.efi替换进旧版本同类项；
 5. 打开新版本Drivers文件夹讲和旧版本相同的子项目拖进旧版本Drivers文件夹；然后打开occ配置器，看有无更新，并选择正确版本号，用occ配置器打开config.plist，升级完成。
 
