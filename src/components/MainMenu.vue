<template>
  <div>
    <ul>
      <li v-for="item in menuItems" :key="item.id">
        <menu-item :name="item.name"/>
      </li>
    </ul>
  </div>
</template>

<script>
import MenuItem from "./MenuItem.vue";

export default {
  components: { MenuItem },
  data() {
    return {
      menuItems: [
        { name: "Zgłoś", id: 1 },
        { name: "Nasza Misja", id: 2 },
        { name: "Kontakt", id: 3 },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
</style>