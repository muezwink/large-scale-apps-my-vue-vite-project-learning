<script setup lang="ts">
  // import a reference to our ItemInterace
  // ItemInterface에 대한 참조를 가져옵니다.
  import type { ItemInterface } from '../../models/items/Item.interface'
  // expose a property called items with a default value of a blank array
  // 기본값이 빈 배열인 항목이라는 프로퍼티를 노출합니다.
  // here replace any[] with ItemInterace[] 
  // 여기서 any[]를 ItemInterface[]로 대체합니다.
  defineProps<{ items: ItemInterface[] }>() 
</script>

<template> 
  <div>
    <h3>Items:</h3>
    <ul>
      <li v-for="(item, index) in items"
        :key="item.id">
        {{item.name}}
      </li>
    </ul>
  </div>
</template>
