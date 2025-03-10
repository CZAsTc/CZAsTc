# 👋 你好，我是 CZAsTc

**Python & GitHub Actions 学习者**  
使用 **Python** 进行自动化任务和天文计算，探索与实践 **GitHub Actions**。

## 🚀 我目前的工作

- 学习 **Python** 开发程序，开发天文计算和地理信息查询等工具。
- 正在学习 **GitHub Actions**，提升开发流程的自动化程度。

## 🔧 我的技能与工具

- **Skyfield**：用于天文计算，进行星体轨道和位置的模拟，进行精确的天文测量。
- **Ephem**：用于计算太阳、月亮等天体的位置，进行天文观测分析。
- **GeoIP2**：进行 IP 地址的地理位置查询，分析 IP 属地。
- **mpmath**：进行高精度的数学计算，支持复杂的数学运算。

## 🔥 最新动态

- 💻 使用 **Skyfield** 进行星体轨迹计算，模拟天体的位置。
- ⚙️ 正在学习并实践 **GitHub Actions**，通过配置工作流实现自动化。
- 🌍 利用 **GeoIP2** 进行 IP 地址的地理位置查询，探索地理信息应用。

## 🧠 我的 GitHub 统计

![我的 GitHub 统计](https://github-readme-stats.vercel.app/api?username=czastc&show_icons=true&locale=cn)

![最常用的语言](https://github-readme-stats.vercel.app/api/top-langs?username=czastc&show_icons=true&locale=cn&layout=compact)

![贡献信息](https://github-readme-streak-stats.herokuapp.com/?user=czastc&locale=zh-Hans)

## 🔗 我的社交平台

- 🌐 [个人网站](https://czastc.pages.dev)

### 🏁 我的 GitHub 项目

- **[AstroKit](https://github.com/CZAsTc/AstroKit)**  
  使用 **Skyfield** 进行星体轨迹计算和天文数据分析，支持卫星轨道的可视化和精确的天文计算。

- **[ProxyGeoConfig](https://github.com/CZAsTc/ProxyGeoConfig)**  
  基于 **GeoIP2** 的 IP 地址地理位置查询工具。

## 🖥️ 随手写的一段 Python 代码

### 使用 Skyfield 计算太阳的位置

```python
from skyfield.api import load

planets = load('de421.bsp')
earth = planets['earth']
sun = planets['sun']

t = load.timescale().now()

astrometric = (earth.at(t)).observe(sun)
alt, az, d = astrometric.apparent().altaz()

print(f"太阳的高度角: {alt.degrees:.2f}°，方位角: {az.degrees:.2f}°")
```

这段代码演示了如何使用 **Skyfield** 来计算太阳的高度角和方位角。😄

🚀 持续探索与学习，让我们一起通过 **Python** 和 **GitHub Actions** 构建高效的自动化工具，提升开发流程。
