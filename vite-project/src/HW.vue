<!-- 
    將以下的表格轉為使用資料，並使用 Vue 進行渲染。

    數量的部分可以點擊，並且調整庫存數量。

    庫存數量不會低於 0。

    新增欄位 “編輯”，按下後可以修改該欄位的品項名稱（按下確認後執行更換）
 -->
<script setup>
    import { ref } from 'vue'
    const products = ref([
        { id:1, item: '珍珠奶茶', desc: '香濃奶茶搭配QQ珍珠', price: 50, stock:20 },
        { id:1, item: '冬瓜檸檬', desc: '清新冬瓜配上新鮮檸檬', price: 45, stock:20 },
        { id:1, item: '翡翠檸檬', desc: '綠茶與檸檬的完美結合', price: 55, stock:20 },
        { id:1, item: '四季春茶', desc: '香醇四季春茶，回甘無比', price: 45, stock:20 },
        { id:1, item: '阿薩姆奶茶', desc: '阿薩姆紅茶搭配香醇鮮奶', price: 50, stock:20 },
        { id:1, item: '檸檬冰茶', desc: '檸檬與冰茶的清新組合', price: 45, stock:20 },
        { id:1, item: '芒果綠茶', desc: '芒果與綠茶的獨特風味', price: 55, stock:20 },
        { id:1, item: '抹茶拿鐵', desc: '抹茶與鮮奶的絕配', price: 60, stock:20 },
    ])
</script>

<template>

</template>

<script>

</script>