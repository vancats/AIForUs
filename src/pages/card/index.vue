<template>
  <NavBar />
  <div h-40 />
  <div
    class="px-20vw rounded-t-3 relative bg-#F4F8FD"
  >
    <div class="absolute -top-5vw left-10vw w-10vw h-10vw bg-blue rounded">
      <span w-full h-full i-carbon:airport-01 />
    </div>
    <div class="absolute -top-4vw left-22vw  text-4xl flex">
      <span text-white>
        ChatGPT
      </span>
      <n-button type="info" class="ml-2 rounded bg-#3A50FF">
        去官网使用
      </n-button>
      <n-button type="info" class="ml-2 rounded bg-#3A50FF">
        去扫码使用
      </n-button>
    </div>
    <div p-4>
      <div text-2xl mb-2>
        关于 Chat GPT
      </div>
      <div break-words text="#5B6681 sm" style="textIndent: 2rem">
        ChatGPT是美国人工智能研究实验室OpenAI新推出的一种人工智能技术驱动的自然语言处理工具，使用Transformer神经网络架构，也是GPT-3.5架构，这是一种用于处理序列数据的模型，拥有语言理解和文本生成能力，尤其是它会通过连接大量的语料库来训练模型，这些语料库包含了真实世界中的对话，使得ChatGPT具备上知天文下知地理，还能根据聊天的上下文进行互动的能力，做到与真正人类几乎无异的聊天场景进行交流。ChatGPT不单是聊天机器人，还能进行撰写邮件、视频脚本、文案、翻译、代码等任务。
      </div>
      <div text-2xl my-4>
        使用方法
      </div>
      <div break-words text="#5B6681 sm" style="textIndent: 2rem">
        ChatGPT是美国人工智能研究实验室OpenAI新推出的一种人工智能技术驱动的自然语言处理工具，使用Transformer神经网络架构，也是GPT-3.5架构，这是一种用于处理序列数据的模型，拥有语言理解和文本生成能力，尤其是它会通过连接大量的语料库来训练模型，这些语料库包含了真实世界中的对话，使得ChatGPT具备上知天文下知地理，还能根据聊天的上下文进行互动的能力，做到与真正人类几乎无异的聊天场景进行交流。ChatGPT不单是聊天机器人，还能进行撰写邮件、视频脚本、文案、翻译、代码等任务。
      </div>
      <img py-2 w-full src="https://img0.baidu.com/it/u=2289446283,2987162055&fm=253&fmt=auto&app=120&f=JPEG?w=1422&h=800">
    </div>
  </div>
</template>

<script setup lang='ts'>

</script>
