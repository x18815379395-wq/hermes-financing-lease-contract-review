# 融资租赁合同审查

融资租赁、售后回租、担保、租赁物购买及相关合同的标准化审查。

## 适用场景

- 融资租赁合同、售后回租合同审查
- 保证合同、抵押合同、质押合同审查
- 租赁物买卖合同审查
- 补充协议及修订条款分析
- 放款前条件落实核查

## 安装

方式一（推荐，通过Hermes技能中心）：

```bash
hermes skills install https://raw.githubusercontent.com/x18815379395-wq/hermes-financing-lease-contract-review/main/SKILL.md
```

方式二（手动安装，从GitHub克隆）：

```bash
git clone https://github.com/x18815379395-wq/hermes-financing-lease-contract-review.git ~/.hermes/skills/financial-risk/financing-lease-contract-review
hermes reload-skills

> 注意：`hermes skills install` 方式需要Hermes Agent支持从GitHub URL安装SKILL.md。若不支持，请使用手动克隆方式。
```

## 使用方法

基于Apache-2.0许可证，改编自CSlawyer1985/claude-for-legal-ZH。支持合同文本路由、修订历史重建、有效条款拼合、法源核实、审批条件识别、租金/费用/保证金/保险条款专项审查，输出金融机构内部风险备忘录。

具体使用方法请参考技能的 `SKILL.md` 文件。

## 许可证

MIT

## 作者

stormchaser
