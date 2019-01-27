# city_picker

A city picker of china, 中国城市选择器

## screenshot

![图片](https://raw.githubusercontent.com/CaiJingLong/asset_for_picgo/master/20190127155034.png)

## use

pubspec.yaml

```yaml
city_picker: ^0.1.0
```

import

```dart
import 'package:city_picker/city_picker.dart';
```

use

```dart
    CityResult result = await showCityPicker(context);
    String province = result?.province; // 省
    String city = result?.city; // 市
    String county = result?.county; // 地级市/县
```
