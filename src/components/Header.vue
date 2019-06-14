<template>
    <div class="row">
        <div class="col-sm12">
            <h3>Citas agregadas</h3>
            <div class="progress">
                <div class="progress-bar" role="progressbar" aria-valuenow="60"
                aria-valuemin="0" aria-valuemax="100"
                :style="{width: (quoteCount/ maxQuote) * 100 + '%'}">
                {{quoteCount / maxQuote}} </div>
                </div>
            </div>
        </div>
</template>
<script>
export default {
    props:['quotesCount', 'maxQuote'],
}
</script>

