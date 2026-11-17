# 广告提示词组织框架

这份参考用于在产品白底图已经完成分析后，把创意转成适合生成模型执行的商业广告提示词。

## 1. 产品锁定

先写产品本身，再写风格：

- same exact product as the reference image
- preserve the original shape, proportions, materials, colors, components and visible branding
- product fully visible, recognizable, commercially retouched
- no redesign, no extra parts, no duplicated product

如果产品有包装或屏幕，写清楚是否保持原有文字和图形。无法确认的文字交给后期排版。

## 2. 广告场景

用“场景 + 动作 + 因果关系”表达创意：

- 场景发生在哪里
- 产品正在做什么或解决什么问题
- 哪个道具能证明产品利益
- 观众应该先看到什么、后理解什么

例如，不要只写“清凉感”，可以写成“透明冰层从产品底部向外扩散，水珠沿外壳滑落，背景是被阳光照亮的浅蓝色泳池边”。

## 3. 构图

尽量说明以下关系：

- 产品占画面的比例
- 产品处于左、中、右哪一侧
- 前景、中景、背景分别放什么
- 文字留白在哪里
- 视觉动线从哪里开始、在哪里停留

适合广告主视觉的常见表达：

- centered hero product shot
- three-quarter view
- low-angle product portrait
- top-down flat lay
- close-up macro detail
- product on the right third, clean negative space on the left for headline

## 4. 商业摄影表达

根据产品和创意选择少量准确的摄影语言：

- studio-quality commercial product photography
- high-end editorial campaign photography
- crisp controlled highlights
- soft diffused key light
- dramatic rim light
- natural window light
- shallow depth of field
- macro detail shot
- clean premium retouching

镜头语言要服务于产品：需要展示结构时使用三分之四视角；需要突出质地时使用微距；需要制造力量感时使用低机位；需要突出使用场景时使用中景或环境肖像。

## 5. 负面提示词

按风险选择，不要机械堆满：

- distorted product, warped geometry, incorrect proportions
- extra parts, missing parts, duplicate product, floating product
- wrong logo, misspelled text, unreadable packaging text
- cheap plastic look, overblown highlights, muddy shadows
- cluttered background, weak subject separation, accidental props
- watermark, random labels, artificial hands, deformed fingers

## 6. 图像与后期的分工

生成模型负责：产品与场景关系、光线、材质、空间、氛围、构图和视觉隐喻。

后期设计负责：准确的 Logo、长文案、价格、规格、二维码、按钮、法务信息和多平台裁切。

因此，提示词通常应要求稳定的产品主体和明确留白，而不是让模型承担所有排版任务。
