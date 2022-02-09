<template>
  <div>
    <h1>ABOUT</h1>
    <Suspense>
      <template #default>
        <userList />
      </template>
      <template #fallback> loading ... </template>
    </Suspense>
  </div>
</template>
