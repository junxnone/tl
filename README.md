# issue2timeline
- based on [visjs](https://github.com/visjs)

## Demo
- default file [demo](https://junxnone.github.io/tl/)
- local file [demo](https://junxnone.github.io/tl/?json=data/food_safety.json)
- http fiel [demo](https://junxnone.github.io/tl/?json=https://gist.githubusercontent.com/junxnone/e50674c433cb7a1cb4dc0688201bcd21/raw/558e808979fd43b7f9b422fed884a282ec4fe5f9/mars_china.json)


## Issue Format

title | starts | ends | groups | types | className | contents
-- | -- |-- |-- |-- | -- | --
天问一号 | 2020-07-23 | now| 中国 |background| |

----

- title: 事件名称
- starts: 开始时间
- ends: 结束时间，`point/box types` 可以不写, `range & background types` 需要，`now` 代表到现在
- groups: 隶属的组别，会自动创建显示在左边栏
- types: point/box(default)/range/background
- className: 可以自定义 item 样式
- contents: 事件详细描述，支持 markdown 链接, contents 中的 markdown 内容会自动转为 `html content`
