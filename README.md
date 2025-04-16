[<img width="300" alt="Mapbox 标志" src="https://static-assets.mapbox.com/www/logos/mapbox-logo-black.png">](https://www.mapbox.com/)

**Mapbox GL JS** 是一个用于网页上交互式、可自定义矢量地图的 JavaScript 库。它采用符合 [Mapbox 样式规范](https://docs.mapbox.com/mapbox-gl-js/style-spec/) 的地图样式，应用到符合 [Mapbox 矢量瓦片规范](https://github.com/mapbox/vector-tile-spec) 的矢量瓦片上，并使用 WebGL 进行渲染。

Mapbox GL JS 是 [跨平台 Mapbox GL 生态系统](https://www.mapbox.com/maps/) 的一部分，该生态系统还包括适用于 [Android](https://docs.mapbox.com/android/maps/overview/)、[iOS](https://docs.mapbox.com/ios/maps/overview/)、[macOS](http://mapbox.github.io/mapbox-gl-native/macos)、[Qt](https://github.com/mapbox/mapbox-gl-native/tree/master/platform/qt) 和 [React Native](https://github.com/mapbox/react-native-mapbox-gl/) 应用程序的兼容原生 SDK。Mapbox 提供构建模块，可将地图、搜索和导航等位置功能添加到您创建的任何体验中。要开始使用 GL JS 或我们的任何其他构建模块，请 [注册 Mapbox 账户](https://www.mapbox.com/signup/)。

除了 GL JS 之外，此存储库还包含 GL JS 和原生 SDK 通用的代码、问题和测试装置。有关原生 SDK 特定的代码和问题，请参阅 [mapbox/mapbox-gl-native](https://github.com/mapbox/mapbox-gl-native/) 存储库。

- [Mapbox GL JS 入门](https://docs.mapbox.com/mapbox-gl-js/overview/)
- [教程](https://docs.mapbox.com/help/tutorials/#web-apps)
- [API 文档](https://docs.mapbox.com/mapbox-gl-js/api/)
- [示例](https://docs.mapbox.com/mapbox-gl-js/examples/)
- [样式文档](https://docs.mapbox.com/mapbox-gl-js/style-spec/)
- [开源样式](https://github.com/mapbox/mapbox-gl-styles)
- [贡献者文档](./CONTRIBUTING.md)
- [浏览器数据存储](./STORAGE.md)

[<img width="600" alt="Mapbox GL JS 地图图库" src="https://static-assets.mapbox.com/www/mapbox-gl-js-gallery.png">](https://www.mapbox.com/mapbox-gljs)

**说明：** （_Mapbox GL JS 地图，从左至右，从上至下_）：自定义样式的点 [聚合](https://docs.mapbox.com/mapbox-gl-js/style-spec/sources/#geojson-cluster)，带点的自定义样式，[Dark 样式](https://www.mapbox.com/maps/dark) 地图上的 [六边形可视化](https://blog.mapbox.com/exploring-nyc-open-data-with-3d-hexbins-5af2b7d8bc46) 及 [`弹出窗口`](https://docs.mapbox.com/mapbox-gl-js/api/markers/#popup)，数据驱动的 [圆形](https://docs.mapbox.com/mapbox-gl-js/style-spec/layers/#circle) 覆盖在带有 [卫星影像](https://docs.mapbox.com/help/getting-started/satellite-imagery/) 的 [`栅格` 图层](https://docs.mapbox.com/mapbox-gl-js/style-spec/layers/#raster) 上，带自定义 [`标记`](https://docs.mapbox.com/mapbox-gl-js/api/markers/#marker) 的 [3D 地形](https://docs.mapbox.com/mapbox-gl-js/example/?topic=3D)，[Mapbox Movement 数据](https://docs.mapbox.com/data/movement/guides/) 可视化。

## 许可证

Mapbox Web SDK

版权所有 © 2021 - 2023 Mapbox, Inc. 保留所有权利。

本存储库中的软件和文件（统称为"软件"）根据 Mapbox 服务条款许可，仅供与 www.mapbox.com/pricing 中列出的相关 Mapbox 产品一起使用。此许可证允许拥有当前有效 Mapbox 账户的开发者根据 Mapbox 服务条款，通过其 Mapbox 账户仅为相关 Mapbox 产品使用和修改软件的授权部分。如果开发者不再拥有良好信誉的 Mapbox 账户或违反 Mapbox 服务条款，此许可证将自动终止。有关许可条款，请参阅 Mapbox 服务条款 https://www.mapbox.com/legal/tos/，其中包含 Mapbox 产品条款 www.mapbox.com/legal/service-terms。如果本软件是 SDK，则不授权更改或干扰与计费、会计或数据收集相关的标记代码部分，且该 SDK 会发送有限的去识别位置和使用数据，这些数据将按照 Mapbox 服务条款使用。[更新于 2023-01]
