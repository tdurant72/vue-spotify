<template>
  <div class="flex flex-col h-screen">
    <div class="bg-blue-500 flex-1 flex overflow-y-hidden">
      <div class="sidebar bg-red-500 w-48 flex-none flex flex-col justify-between">
        <div>one</div>
        <div
          class="overflow-y-auto"
        >Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quam, asperiores fugiat! Corporis perspiciatis alias eligendi consectetur totam in, fugit ullam odio animi odit recusandae. Maiores voluptatem deserunt similique alias veritatis odio delectus officiis veniam aut exercitationem quia, autem mollitia itaque obcaecati asperiores perspiciatis impedit. Error fugiat repellat eos? Iste cumque voluptates impedit, aspernatur ipsa dolorem debitis magni odit, soluta nisi consectetur? Aperiam cumque est accusamus asperiores non tenetur saepe. Culpa at obcaecati incidunt eius ut laudantium quam odio corrupti animi! Numquam, eaque! Sunt vitae accusamus harum officia eveniet voluptatibus quam? Soluta voluptate, laboriosam similique perspiciatis excepturi quam repellendus eum voluptas, labore voluptates id tempora molestiae perferendis sapiente earum rem modi, cumque dignissimos minus qui quidem. Corrupti voluptas soluta, illum excepturi eaque quidem ex asperiores iusto obcaecati voluptates dolores officiis reiciendis saepe magnam! Esse error, dolorum officia, fugiat unde eveniet laborum impedit repellendus minus quos numquam amet magnam at eum sequi deserunt doloribus, libero pariatur aspernatur. Quo sunt praesentium, architecto veritatis nobis quas laborum amet ratione cumque enim ex dolorem! Debitis est error a officia optio assumenda, fuga sunt, quia nesciunt ex commodi accusantium voluptates eaque unde! Nesciunt, magni libero distinctio sint rerum maxime placeat, nam, est tempora optio recusandae! Libero provident alias, labore tenetur ad iusto! Quibusdam, voluptatum voluptatibus? Illum accusantium velit sunt ipsum vel eos suscipit dolorum saepe quas labore, quaerat facere cupiditate voluptatem ipsam sint voluptate natus tempore ea voluptates beatae architecto? Excepturi non odit quo. Totam error doloremque odit tempore natus aspernatur voluptatibus iusto et assumenda deleniti!</div>
        <div>three</div>
      </div>
      <div class="content-area bg-red-300 flex-1 overflow-y-auto">content area</div>
    </div>
    <div class="bg-blue-300"></div>
  </div>
</template>

<script>
export default {};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
