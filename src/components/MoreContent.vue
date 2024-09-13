<template>
  <div class="more-content">
    <ul class="custom-ul">
      <li class="custom-li">
        Whenever you feel like criticizing any one, just remember that all the people in this world
        haven't had the advantages that you've had.
      </li>
      <li class="custom-li">
        He stretched out his hand desperately as if to snatch only a wisp of air, to save a fragment
        of the spot that she had made lovely for him.
      </li>
      <li class="custom-li">
        So we beat on, boats against the current, borne back ceaselessly into the past.
      </li>
    </ul>
  </div>
</template>

<style lang="scss" scoped>
.more-content {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 20px;
  width: 100%;
  height: 100%;
}
.custom-ul {
  display: flex;
  flex-wrap: wrap; /* 自动换行 */
  // list-style-type: none; /* 去掉默认的圆点样式 */
  padding: 0;
  margin: 0;
}
.custom-li {
  margin: 10px;
  padding: 15px;
  flex: 1 1 200px; /* 每个项目最小宽度为200px，自动调整 */
  text-align: center;
  border-radius: 8px;
}
@media screen and (max-width: 768px) {
  .custom-li {
    flex: 1 1 100%; /* 在小屏幕上，每个项目最小宽度为100% */
  }
}
</style>
