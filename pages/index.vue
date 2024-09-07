<template>
  <main>
    <NuxtErrorBoundary>
      <Button />
      <template #error="{ error }">
        <p>Something went wrong! {{ error }}</p>
      </template>
    </NuxtErrorBoundary>
  </main>
</template>
