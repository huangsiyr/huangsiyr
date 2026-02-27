- 👋 Hi, I’m @huangsiyr
- 🌱 I’m currently learning python and R


- 最新更新的1929年至2023年12月31日GSOD全球逐日气象站点数据，供大家研究使用。

数据指标GSOD 数据是覆盖全球的天气数据的宝贵来源，从1929年至今，包括全球超9000个站点的气象观测数据。

字段	字段说明
气象站代码STATION	站点编号（WMO/DATSAV3 可能与 WBAN 编号结合）
日期DATE	日期格式为 mm/dd/yyyy
纬度LATITUDE	纬度以十进制度表示（南半球的值为负数）
经度LONGITUDE	经度以十进制度表示（西半球的值为负数）
气象站高程ELEVATION	海拔高度，单位为米
气象站名称NAME	气象站/机场/军事基地的名称
平均气温TEMP	当日平均气温，以华氏度及其十分位表示。缺失值为 9999.9
平均气温属性TEMP_ATTRIBUTES	参与平均温度计算的观测值个数
平均露点DEWP	单位Fahrenheit华氏度，精确到一位小数，缺失值9999.9
平均露点属性DEWP_ATTRIBUTES	参与平均露点计算的观测值个数
平均海平面压强SLP	平均海平面压强，单位mb毫巴mbar，1mb=1hPa百帕斯卡，缺失值9999.9
平均海平面压强属性SLP_ATTRIBUTES	参与平均海平面压强计算的观测值个数
平均观测站压强STP	平均测站压强，单位mb毫巴mbar，缺失值9999.9
平均观测站压强属性STP_ATTRIBUTES	参与平均测站压强计算的观测值个数
平均能见度VISIB	平均能见度，单位miles英里，缺失值999.9
平均能见度属性VISIB_ATTRIBUTES	参与平均能见度计算的观测值个数
平均风速WDSP	单位knots节（海里/小时），缺失值999.9
平均风速属性WDSP_ATTRIBUTES	参与平均风速计算的观测值个数
最大持续风速MXSPD	单位knots节，缺失值999
最大持续风速属性	参与最大持续风速计算的观测值个数
最大阵风速度GUST	当日报告的最大阵风速度，以节及其十分位表示。缺失值为 999.9
最高气温MAX	单位Fahrenheit华氏度，缺失值9999.9 PS.最高气温报告的时间因国家和地区而异，因此有时可能不是当日的最高值。
最高气温属性MAX_ATTRIBUTES	空值：自动观测到的最低温度； 星号，从逐小时数据中提取得到的最低温度
最低气温MIN	单位Fahrenheit华氏度 PS. 最低气温报告的时间因国家和地区而异，因此有时可能不是当日的最低值。
最低气温属性MIN_ATTRIBUTES	空值：自动观测到的最低温度； 星号，从逐小时数据中提取得到的最低温度
降水量PRCP	（雨或融化的雪），单位inches英寸，缺失值99.99，“0”值表示当日没有测量到降水
降水量属性PRCP_ATTRIBUTES	A，1 report of 6-hour precipitation amount. B，Summation of 2 reports of 6-hour precipitation amount. C，3次报告6小时降水量的和 D，4次报告6小时降水量的和 E，1次报告12小时降水量 F，2次报告12小时降水量的和 G，1次报告24小时降水量 H，气象站报告当日降水量为0，但是在逐小时观测中报告了至少一次降水，可能是当日数据不完整 I，气象站当日没有报告任何降水，逐日观测中也没有报告任何降水，但是仍然可能存在降水只是没有被报告
积雪深度SNDP	单位inches英寸，取当日最后一次观测值（如果观测了多次），缺失值999.9
指示器FRSHTT	当期报告的天气情况，是否有雾Fog(‘F’-1st digit)、雨Rain or Drizzle(‘R’-2nd digit)、雪Snow or Ice Pellets(‘S’-3rd digit)、冰雹Hail(‘H’-4th digit)、雷Thunder(‘T’-5th digit)、龙卷风或漏斗云Tornado or Funnel Cloud(‘T’-6th digit)。 1，有 0，没有
