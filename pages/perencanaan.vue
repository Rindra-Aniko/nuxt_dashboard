<template>
    <div class="flex min-h-full flex-col justify-center px-6 py-12 lg:px-8">
       <AnalyticsCharts />
    </div>
</template>

<script setup>
definePageMeta({
    middleware:['auth']
})

</script>