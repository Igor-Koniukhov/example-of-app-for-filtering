<template>
    <base-card>
    <h2>Find Your Coach</h2>
    <span class="filter-option">
        <input type="checkbox" id="frontend" checked>
        <label for="frontend">Frontend</label>
    </span>
    <span class="filter-option">
        <input type="checkbox" id="backend" checked>
        <label for="backend">Backend</label>
    </span>
    <span class="filter-option">
        <input type="checkbox" id="career" checked>
        <label for="career">Career</label>
    </span>
    </base-card>
</template>
<script>
export default{
    data(){
        return {
            filters:{
                frontend: true,
                backend: true,
                career: true
            }
        }
    }
}
</script>