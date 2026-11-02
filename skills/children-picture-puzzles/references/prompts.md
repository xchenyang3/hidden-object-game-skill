# 按任务使用的提示词

把方括号字段替换成当前需求；自然语言、中文或英文均可，不强制照抄整套。生成前先确定目标的辨认结构。提示词不是完成核查的证据。

## 新建隐藏物品图

Use case: illustration-story.
Create ONE coherent hidden-object puzzle illustration for a children's activity book.
Audience: [ages]. Scene: [setting and character actions].
Style: [user's chosen style]. For black-and-white line art: crisp black contours on white, controlled detail density, no grey wash, no large black filled areas, consistent line weight.
Composition: [orientation, foreground/midground/background]. Keep believable actions and clear silhouettes amid abundant detail.
Embed [count] of each target: [target + distinctive structural features].
Hide using rotation, visual similarity, shared contours, patterned surfaces and limited occlusion. Targets must remain identifiable at the intended print size. Do not display them as isolated icons or obvious functional props.
Suggested camouflage: [per-target idea]. These are design intentions, not verified answer locations.
Avoid duplicate target-like objects in the surrounding scene.
Student picture only: no answer rings, arrows, numbers or labels. No watermark.

## 把显眼目标藏得更好

Edit target: [actual existing image].
Preserve the approved composition, linework style and characters.
Remove or replace the conspicuous targets at [observed locations] with ordinary scene content.
Re-hide the same targets in [candidate locations], matching nearby scale, angle and line weight. Use [chosen camouflage] while retaining [recognition features].
Difficulty should come from visual integration, NOT illegibly small size, incomplete geometry, or clutter without readable contours.
No answer markings. Preserve non-target regions as closely as possible.
After editing, inspect actual positions and counts anew.

优先一次修正一个明确问题；多个目标都太显眼时可统一修订。不要坚持错误藏法：电池失去接点像餐巾，就换藏法或重画；芯片只有菱形外框，就补上可辨的引脚。

## 两图找不同B图

Edit target: approved image A.
Create B with ONLY these localized differences: [numbered specific changes].
Keep all other composition, faces, hands, props, linework, crop and scale identical.
No new decorative changes, no text, no answer rings.
Intended differences should survive the requested black-and-white printing and reduction size.

执行后对照图像；若人物脸部、背景纹理等也变了，不把它们悄悄忽略为“无关变化”。需要记录或修复。

## 答案图

Edit target: the final verified student image [version].
Add ONLY thin [color] rings/ellipses and numbers at the actual verified target regions.
Image dimensions: [W x H].
[ID, target/difference, actual bbox or center and ring size].
Keep original drawing, object positions, image crop and dimensions unchanged. Place numbers beside rings without obscuring objects.
No new target items, no restyling, no relocated elements.
Use the exact current puzzle version, not an earlier draft.

将图像按给定参考重新生成仍可能产生变动。必须检查输出，不能仅凭“preserve exactly”的提示词宣称像素一致。

## 最小检验清单

1. 不看原藏匿计划，能否在实际图中找到每个目标？
2. 识别依据是否在图中可见？
3. 有无额外的相同目标或可混淆物？
4. 答案圈是否准确，是否挡住特征，是否对应同一版本？
5. 复杂度是否仍有视觉层次，缩印后能否辨认？
6. 两图题是否出现计划之外的变化？
7. 不确定项明确标为待核对，而不是凭空补位置。
