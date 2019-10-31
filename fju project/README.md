# FJU 大三專題 layout

* PCB layout 正面
<p align="left">
    <img src="https://github.com/405250553/PCB-layout/blob/master/fju%20project/%E6%88%90%E5%93%81%E7%9B%B8%E9%97%9C%E6%AA%94%E6%A1%88/%E6%88%90%E5%93%81%E6%AD%A3%E9%9D%A2.png" alt="Sample"  width="400" height="400">
    <p align="left">
    </p>
</p>

* PCB layout 背面
<p align="left">
    <img src="https://github.com/405250553/PCB-layout/blob/master/fju%20project/%E6%88%90%E5%93%81%E7%9B%B8%E9%97%9C%E6%AA%94%E6%A1%88/%E6%88%90%E5%93%81%E8%83%8C%E9%9D%A2.png" alt="Sample"  width="400" height="400">
    <p align="left">
    </p>
</p>

When using debug mode you don't need to specify versions for hardware and firmware, so you can develop without having to worry about versioning your application. If you want to generate a package for production, you will need to do so without the `--debug-mode` parameter and specify the versions:
```
nrfutil pkg generate --hw-version 51 --sd-req 0x80 --application-version 4 --application app.hex --key-file key.pem app_dfu_package.zip
```


