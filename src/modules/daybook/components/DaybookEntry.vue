<template>
    <div @click="$router.push({name: 'entry', params: {id: 10} })" class="mb-3 entry-container pointer p-2">
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">16</span>
            <span class="mx-1 fs-5">Abril</span>
            <span class="mx-2 fw-light">2023, domingo</span>
        </div>
        <div class="entry-description">
            Est incididunt proident enim nostrud fugiat deserunt nostrud irure voluptate. Tempor ullamco et nisi proident eiusmod ex tempor velit quis et ea ad mollit eu. Veniam proident minim esse incididunt non Lorem deserunt dolore enim cillum aliqua incididunt excepteur. Ex irure velit reprehenderit elit aute elit ex exercitation elit tempor pariatur incididunt. Id ullamco anim culpa commodo ex reprehenderit eiusmod pariatur id culpa. Veniam laborum Lorem dolore ex consectetur minim ut et dolor sunt cupidatat magna duis. Incididunt labore adipisicing adipisicing tempor fugiat aute pariatur.
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .entry-container {
        border-bottom: 1px solid #2c3e50;
        transition: 0.2s all ease-in;
        &:hover {
            background-color: lighten($color: grey, $amount: 45);
            transition: 0.2s all ease-in;
        }
        .entry-description {
            font-size: 12px;
        }
    }
    
    
</style>