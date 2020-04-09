<template>
  <component :is="'Contact'">
    <p>Hola!</p>
    <VueRemarkContent>
        <template v-slot:tags>
          <ul>
            <li>
              foo
            </li>
          </ul>
          <slot />
        </template>
    </VueRemarkContent>
  </component>
</template>
