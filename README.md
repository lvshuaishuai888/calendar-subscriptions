# 日历订阅 Calendar Subscriptions

独立维护个人使用的 iCalendar（`.ics`）订阅：按年份保存中国大陆节假日与调休补班安排，另设生日纪念日日历目录。

## 2027 年节假日订阅

| 日历 | 内容 | iPhone 颜色 |
| --- | --- | --- |
| [放假日历](https://raw.githubusercontent.com/lvshuaishuai888/calendar-subscriptions/main/holidays/2027/holidays.ics) | 官方放假区间，共 29 天 | 绿色 |
| [调休补班日历](https://raw.githubusercontent.com/lvshuaishuai888/calendar-subscriptions/main/holidays/2027/workdays.ics) | 调休补班，共 5 天 | 红色 |

**绿色放假日历地址**

```text
https://raw.githubusercontent.com/lvshuaishuai888/calendar-subscriptions/main/holidays/2027/holidays.ics
```

**红色补班日历地址**

```text
https://raw.githubusercontent.com/lvshuaishuai888/calendar-subscriptions/main/holidays/2027/workdays.ics
```

在 iPhone“日历”App 中，打开“日历 → 添加日历 → 添加订阅日历”，分别粘贴上述地址，选择对应颜色。如需跨设备同步，账户选择 iCloud。颜色以手机端选择为准；两份文件均为每天一条全天日程，不设置事件提醒。

如果已订阅 `adrule` 仓库的旧地址，请取消旧订阅后改用本仓库地址，避免重复显示。旧仓库文件暂时保留，现有旧订阅仍可使用。

[2027 年日期清单和官方来源](holidays/2027/README.md) · [Apple 官方订阅说明](https://support.apple.com/zh-cn/102301)

## 目录结构

```text
calendar-subscriptions/
├── README.md
├── holidays/
│   └── 2027/
│       ├── README.md
│       ├── holidays.ics
│       └── workdays.ics
└── birthdays/
    └── README.md
```

## 后续年份

2028 年及以后的日历，待官方公布安排并核实后，新增到 `holidays/<年份>/`，继续分别提供 `holidays.ics` 和 `workdays.ics`。本次仅发布 2027 年；没有创建 2028 年预测日历或可订阅文件。

不同年份拥有独立订阅地址。订阅 2027 年不会自动获得 2028 年，需要在新年份发布后添加对应订阅。现有年份文件的修改会通过原地址提供，客户端刷新可能受网络及缓存影响。

## 生日与纪念日

[`birthdays/`](birthdays/README.md) 预留给以后单独维护的生日纪念日日历，目前没有生日数据或可订阅文件。

本仓库公开，提交的姓名、生日和备注会对所有人可见，并可能留存在 Git 历史中。私密生日资料应通过私有存储或仅本地导入方式管理，勿提交到本公开仓库。
