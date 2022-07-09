<script setup lang="ts">
import {ref} from "vue"

type Data = {
	id: number;
	sudah: boolean;
	isi: string;
}

const data: Ref<Data[]> = ref([
	{
		id: Math.random(),
		sudah: false,
		isi: ""
	}
])
</script>

<template>
	<div class="w-full min-h-screen bg-slate-800 text-white">
 	 <p>Hello world</p>
 	</div>
</template>
