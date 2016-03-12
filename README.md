# AndroidPublicXmlCompat
Enable 'public.xml' feature on gradle plugin version is higher than 1.3.0, 2.0.0 or later is available for testing.<br />
在gradle plugin 高于1.3.0的版本上启用public.xml特性，2.0.0以上版本已测试可用

1. Copy the public-xml.gradle App module to the next directory.<br />
  复制public-xml.gradle到App模块目录下

2. Add this line into your App module's build.gradle: <br />
  在App模块的build.gradle 中增加:

   apply from: 'public-xml.gradle'
