## Day1

https://chatgpt.com/share/ceb7cc79-e3c4-4e3e-ad0c-b6e2e470f301

## Day2

### 1.1 image

[gpt-4v.jpg](openai_api/images/gpt-4v.jpg)

### 1.2 query_base64_image_description

[openai_api/gpt-4v.ipynb](openai_api/gpt-4v.ipynb)

这是一页手写笔记，内容主要涉及西方哲学的重点概念和观点。以下是内容的摘要与总结：

1. **引言部分**：
   - 提出西方哲学的起源和发展，强调其对社会和思想的影响。

2. **主要观点**：
   - 讨论哲学家如何定义“人”及人的存在方式，并指出权力和责任的关系。
   - 强调自由意志的重要性，以及个体在社会中的角色。

3. **应用示例**：
   - 提出自由和个体意识的关联，讨论相对主义与绝对主义的辩论。

4. **其他内容**：
   - 提及对哲学的一些基本理解，并提醒注意历史和社会背景对哲学思想的影响。

**总结**：
这份笔记深入探讨了西方哲学中的核心思想，特别是关于个体自由、社会角色和权力结构的关系，对理解西方思想发展具有重要意义。

### 1.3 Markdown format:

这是一页手写笔记，内容主要涉及西方哲学的重点概念和观点。以下是内容的摘要与总结：

1. **引言部分**：
   - 提出西方哲学的起源和发展，强调其对社会和思想的影响。
2. **主要观点**：
   - 讨论哲学家如何定义“人”及人的存在方式，并指出权力和责任的关系。
   - 强调自由意志的重要性，以及个体在社会中的角色。
3. **应用示例**：
   - 提出自由和个体意识的关联，讨论相对主义与绝对主义的辩论。
4. **其他内容**：
   - 提及对哲学的一些基本理解，并提醒注意历史和社会背景对哲学思想的影响。

**总结**： 这份笔记深入探讨了西方哲学中的核心思想，特别是关于个体自由、社会角色和权力结构的关系，对理解西方思想发展具有重要意义。

### 2.1 Ai translator

[langchain/openai-translator/logs/translation.log](langchain/openai-translator/logs/translation.log)

Translator to Chinese and Korea

```
Table Testing
2024-07-24 14:16:26.542 | DEBUG    | translator.pdf_parser:parse_pdf:54 - [table]
[Fruit, Color, Price (USD)] [Apple, Red, 1.20] [Banana, Yellow, 0.50] [Orange, Orange, 0.80] [Strawberry, Red, 2.50] [Blueberry, Blue, 3.00] [Kiwi, Green, 1.00] [Mango, Orange, 1.50] [Grape, Purple, 2.00]
2024-07-24 14:16:33.624 | DEBUG    | book.content:set_translation:54 - [translation]
[과일, 색상, 가격 (USD)] [사과, 빨간색, 1.20] [바나나, 노란색, 0.50] [오렌지, 주황색, 0.80] [딸기, 빨간색, 2.50] [블루베리, 파란색, 3.00] [키위, 초록색, 1.00] [망고, 주황색, 1.50] [포도, 보라색, 2.00]
2024-07-24 14:16:33.630 | DEBUG    | book.content:set_translation:63 - [translated_df]
     과일   색상 가격 (USD)
0    사과  빨간색      1.2
1   바나나  노란색      0.5
2   오렌지  주황색      0.8
3    딸기  빨간색      2.5
4  블루베리  파란색      3.0
5    키위  초록색      1.0
6    망고  주황색      1.5
7    포도  보라색     2.00

Table Testing
2024-07-24 14:13:20.064 | DEBUG    | translator.pdf_parser:parse_pdf:54 - [table]
[Fruit, Color, Price (USD)] [Apple, Red, 1.20] [Banana, Yellow, 0.50] [Orange, Orange, 0.80] [Strawberry, Red, 2.50] [Blueberry, Blue, 3.00] [Kiwi, Green, 1.00] [Mango, Orange, 1.50] [Grape, Purple, 2.00]
2024-07-24 14:13:25.819 | DEBUG    | book.content:set_translation:54 - [translation]
[水果, 颜色, 价格 (美元)] [苹果, 红色, 1.20] [香蕉, 黄色, 0.50] [橙子, 橙色, 0.80] [草莓, 红色, 2.50] [蓝莓, 蓝色, 3.00] [奇异果, 绿色, 1.00] [芒果, 橙色, 1.50] [葡萄, 紫色, 2.00]
2024-07-24 14:13:25.822 | DEBUG    | book.content:set_translation:63 - [translated_df]
    水果  颜色 价格 (美元)
0   苹果  红色     1.2
1   香蕉  黄色     0.5
2   橙子  橙色     0.8
3   草莓  红色     2.5
4   蓝莓  蓝色     3.0
5  奇异果  绿色     1.0
6   芒果  橙色     1.5
7   葡萄  紫色    2.00
```

### 3.1 Extend langchain chains

[langchain/jupyter/chains/router_chain.ipynb](/langchain/jupyter/chains/router_chain.ipynb)

Based on original code, add biology_template, computer_science_template, chinese_literature_template 

## Day3

Add healthy_sales_chatbot: [langchain/healthy_sales_chatbot](langchain/healthy_sales_chatbot)



Add laptop_sales_chatbot: [langchain/laptop_sales_chatbot](langchain/laptop_sales_chatbot)



