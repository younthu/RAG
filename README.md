# RAG
RAG搭建方案及效果评估.

# 方案列表

候选方案:
1. https://zhuanlan.zhihu.com/p/671853034
   1. 英文原文: https://dev.to/worldlinetech/rag-tutorial-exploring-anythingllm-and-vector-admin-4i3c 
2. https://docs.mistral.ai/guides/rag/ 
3. https://github.com/Mintplex-Labs/anything-llm, 15.8k stars
4. Haystack：一个开源的问答系统，支持各种语言模型和文档存储后端。 14.2k stars
5. OpenKM：一个开源的文档和知识管理系统，支持文档管理和知识库功能。
6. Askbot：基于 Django 的问答系统，类似于 Stack Overflow。 
7. Zulip：一个开源的团队聊天工具，具有很好的知识管理功能。
8. https://www.ddhigh.com/2024/04/28/llama3-rag-tutorial/ , 基于llama3和langchain使用RAG搭建你的私有知识库！
9. https://juejin.cn/post/7359567256592777251, 从零开始学 langchain 之搭建最小的 RAG 系统

方案笔记:

<table> 
  <tr>
    <th>AnythingLLM + Vector Admin</th>
  </tr>
  <tr>
     <td>
        难度: ★★★★☆ 
        效果: ★★☆☆☆ 
        licebse: MIT
        是否要写代码: 不要
        其它: 需要用Mistral AI的api, 不属于私有部署
        链接: https://docs.mistral.ai/guides/rag/
     </td>
  </tr>
  <tr>
    搭建复杂.里面用了faiss, A library for efficient similarity search and clustering of dense vectors.
  </tr>
  <tr>
    <th>Mistral Basic RAG</th>
  </tr>
  <tr>
     <td>
        难度: ★☆☆☆☆ 
        效果: ★☆☆☆☆ 
        是否要写代码: 要
        其它: 需要用Mistral AI的api, 不属于私有部署
        链接: https://docs.mistral.ai/guides/rag/
     </td>
  </tr>
  <tr>
     搭建简单，有现成的colab文件，CPU就能跑，推理在mistral的服务器上进行。
     
     建议直接运行[官方colab文件](https://colab.research.google.com/github/mistralai/cookbook/blob/main/basic_RAG.ipynb), 不建议自己在本地折腾环境了。
  </tr>
  </table>




