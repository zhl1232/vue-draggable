<template>
	<Draggable v-model="cardList" :disabled="!dragSwitch"
	    @on-sort-ready="dragready" @on-sort-start="dragstart" @on-sort-end="dragend">
	    <template slot-scope="{item, index}">
	         <p>place your content here</p>              
	    </template>
	</Draggable>
</template>
<script>
import Draggable from './src/draggable';
</script>