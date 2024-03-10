<template>
  <main>
    <PagesHomeHero />
    <MainSection :gap="40">
      <div class="flex justify-center items-center">
        <div class="p-5 basis-1/2 text-center">
          <MainHeading :size="5"> Heeeeeeey </MainHeading>
        </div>
        <div class="p-5 basis-1/2 text-right">
          <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ex
            quisquam veritatis et voluptate at, fugiat quae nobis asperiores
            accusantium! Dolorem voluptates pariatur officiis voluptatibus
            voluptatum perferendis ipsam facere recusandae eaque!
          </p>
        </div>
      </div>
    </MainSection>
    <MainSection :gap="20">
      <div class="flex justify-center items-center">
        <div class="p-5 basis-1/2 text-right">
          <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ex
            quisquam veritatis et voluptate at, fugiat quae nobis asperiores
            accusantium! Dolorem voluptates pariatur officiis voluptatibus
            voluptatum perferendis ipsam facere recusandae eaque!
          </p>
        </div>
        <div class="p-5 basis-1/2 text-center">
          <MainHeading :size="5"> Heeeeeeey </MainHeading>
        </div>
      </div>
    </MainSection>
  </main>
</template>
