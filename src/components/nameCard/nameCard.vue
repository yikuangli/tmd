<template>
    <vrow>
        <vcol span = "24">
        <vpanel :title="t" desc="描述信息" status="状态">
            <view>{{inside}}</view>
        </vpanel>
        </vcol>
    </vrow>
    
</template>

<script>
export default {
  props: [ 't', 'inside' ]
}
</script>

