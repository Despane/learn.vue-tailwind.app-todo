<script setup>
import { CheckCircleIcon } from '@heroicons/vue/16/solid/index.js'
import {
	ChartBarIcon,
	ClockIcon,
	ListBulletIcon,
} from '@heroicons/vue/24/outline/index.js'
</script>

<template>
	<header
		class="sticky top-0 z-10 flex items-center justify-between border-b bg-white p-3"
	>
		<a href="#">
			<img src="./assets/img/logo.svg" alt="Logo" class="w-30 h-20" />
		</a>
		<a href="#">
			<div v-if="true" class="flex items-center gap-1 text-sm">
				Day Complete!
				<CheckCircleIcon class="h-7 text-green-500" />
			</div>
			<div v-else class="flex items-center gap-1 text-sm">
				<div>Progress <span class="font-mono">20%</span></div>
				<div class="h-3 w-3 rounded-full bg-red-500"></div>
			</div>
		</a>
	</header>
	<main class="flex flex-grow flex-col">
		Lorem ipsum dolor sit amet, consectetur adipisicing elit. A accusamus,
		adipisci alias aliquid asperiores at cum deserunt eos fuga fugiat laborum
		maxime modi natus neque nihil quam quasi quod quos reiciendis repellat
		sapiente sequi similique sint sit unde veniam voluptas! Accusamus commodi
		cum, deleniti dolores doloribus eius, error incidunt iste laboriosam minus
		nesciunt obcaecati quod ullam, veritatis vero! Cum est praesentium sed unde?
		Adipisci architecto dicta fugit ipsum iure nostrum, odio odit omnis, optio,
		perferendis quam quia quibusdam reiciendis sequi similique voluptatem
		voluptatum? Accusantium at eveniet molestias, omnis praesentium quam sed
		voluptatum. Alias beatae, consectetur cupiditate debitis dolores, doloribus
		eaque est hic ipsum itaque iure laboriosam magnam magni molestias natus
		neque optio perferendis quas quisquam quo quod quos sapiente sequi totam
		veritatis voluptate voluptatum! Accusantium beatae culpa, error id illo
		minus non provident reprehenderit tempore ut. Accusantium ad cupiditate,
		debitis, distinctio dolor, doloribus ex facilis fugit incidunt molestiae
		odio porro voluptatem. Aspernatur, laudantium nobis obcaecati quidem
		similique totam voluptas voluptatibus! Accusantium delectus, exercitationem!
		Accusamus accusantium amet asperiores consequatur culpa delectus deserunt,
		dolorum eligendi enim eos eum ipsa itaque iusto labore magni minus neque
		nulla odio possimus, praesentium quam quasi repellendus sequi vel
		voluptatibus? Aliquam animi cum cupiditate dicta, est iure iusto minus nam
		nemo quam quas qui, quibusdam sapiente sequi, unde vel velit. Ad alias,
		animi, dignissimos dolorem est eveniet ex impedit incidunt ipsam iste
		laboriosam natus, officia porro quas quibusdam sapiente sequi sint
		temporibus ut voluptatibus? Adipisci at debitis eveniet, fugit illum, in
		magnam officiis praesentium quis sapiente voluptas voluptatibus? Beatae
		delectus dolorem ex explicabo illum quaerat, quia quo reiciendis ut velit
		veniam voluptatum. A aliquam, aut corporis debitis dolores expedita hic
		neque nostrum quaerat quos! Eveniet libero modi quidem. Accusamus aliquam
		at, consequuntur delectus dolorum ducimus illum ipsa modi molestias officia
		placeat quam quidem, ratione reprehenderit ut, vitae voluptas! Ab ad,
		architecto aspernatur dicta earum, et expedita facere incidunt iure, minima
		mollitia omnis optio quibusdam quis tenetur ullam vel. Dolorem dolorum eaque
		earum est ipsam minus odio officiis perspiciatis quam quasi, quia quo
		reiciendis, repellendus suscipit voluptate? Ab aliquam aliquid eos harum
		ipsa laudantium molestiae numquam quas quidem sint? Ab ad, commodi, delectus
		ea, esse eum hic laudantium non numquam rem sed suscipit voluptatem? Ad,
		dolor enim incidunt nam nulla odio possimus quaerat quas quo reiciendis
		sunt, tempora voluptas voluptates. Animi aut consequuntur corporis ducimus,
		eos facilis harum natus pariatur quidem rerum sed sit tenetur unde
		veritatis, vero.
	</main>
	<nav class="sticky bottom-0 z-10 bg-white">
		<ul class="flex items-center justify-around border-t">
			<li class="flex-1">
				<a
					class="flex flex-col items-center p-2 text-xs capitalize"
					href="#timeline"
				>
					<ClockIcon class="h-6 w-6" />
					Timeline</a
				>
			</li>
			<li class="flex-1">
				<a
					class="flex flex-col items-center p-2 text-xs capitalize"
					href="#acivities"
				>
					<ListBulletIcon class="h-6 w-6" />
					Activities</a
				>
			</li>
			<li class="flex-1">
				<a
					class="flex flex-col items-center p-2 text-xs capitalize"
					href="#progress"
				>
					<ChartBarIcon class="h-6 w-6" />
					Progress</a
				>
			</li>
		</ul>
	</nav>
</template>
