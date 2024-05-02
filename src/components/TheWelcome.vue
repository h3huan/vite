<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Houdini</template>

    Houdini的
    <a href="https://www.sidefx.com/" target="_blank" rel="noopener">官网</a>
    有几乎所有节点的使用说明，如果有一些事关底层技术或者未能及时修复的 bug 导致的节点矛盾，也基本能在此找到，很好，没问题，只是我过于菜了。
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Maya</template>

    Maya 几乎是我接触过的最难以替代的工具。尽管其他同行的产品也不能说不好，Maya 也不见得样样优于他们，譬如同样优秀的
    <a href="https://www.blender.org/" target="_blank" rel="noopener">Blender</a>
    。但不同点在于 Maya 的缺点对于我来讲基本可以说不痛不痒。尽管目前钟意于用
    <a href="https://docs.chaos.com/category/vray" target="_blank" rel="noopener">Vray</a>
    这种老东西的我应该代表不了很多人，但逃离“刻板印象”本身就是我的一个动机。
    <br />

    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Unreal Engine</template>

    事实上，这个我机器中最大的软件，我对它的理解应该还过于浅薄。但它是我提起劲来学本页提到的众多软件的核心理由。
    在最近一年，我以极低的效率在重新学习
    <a href="https://www.learncpp.com/" target="_blank" rel="noopener">C++</a>,
    <a href="https://vue3js.cn/" target="_blank" rel="noopener">Web 开发</a>,
    <a href="http://www.yanhuangxueyuan.com/threejs/examples/#webgl_animation_keyframes" target="_blank" rel="noopener">模型资产</a>, 还有大量的
    <a href="https://nav.guidebook.top/wenxian" target="_blank" rel="noopener">艺术理论</a>。
    效率基本可以说终于让我意识到自己智力平庸。目前我正在试着用这个软件实现游戏脚本编程，实现独立
    <a href="https://www.vg-resource.com/" target="_blank" rel="noopener">游戏开发</a>
    是我现阶段的终极目标。
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Coding</template>

    实现我大部分项目目标时，最经常成为绊脚石的理由正是“代码”。现在
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Vue</a>是现在走出的第一步。最近才了解到
    <a href="https://github.com/h3huan" target="_blank" rel="noopener"
      >Github</a
    >的作用，最近上传了一些东西，乐此不疲。后面
    <a href="https://www.zhihu.com/column/c_1249465121615204352" target="_blank" rel="noopener">图形学</a>和
    <a href="https://www.rust-lang.org/" target="_blank" rel="noopener">Rust</a>
    是我打算试一下的方向。
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Arts</template>

    其实我直到不久之前都从未打算做一个“程序员”。我的自我认同是“艺术家”，但我其实画画稀烂。在这段时间里，
    我主动寻找了大量艺术理论的书本，每天不定时让自己浸泡在这些语法复杂的定论中。后来我也试着去学一下绘画，
    用自己囤积的多套课程，多半半途而废。
  </WelcomeItem>
</template>
