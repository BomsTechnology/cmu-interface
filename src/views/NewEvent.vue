<script setup>
import Header from '../components/Header.vue'
import SubHeader from '../components/SubHeader.vue'
import Footer from '../components/Footer.vue';
</script>

<template>
<Header/>
<SubHeader :title="'News & Events'"/>
<div class="px-8 mt-8 mb-8">
    <div class="flex w-full border-0 border-b border-gray-300">
        <button class="flex items-center h-12 px-4 py-2 md:text-sm text-xs  text-center text-gray-700 bg-transparent sm:text-base dark:border-gray-500 dark:text-white whitespace-nowrap cursor-base focus:outline-none hover:border-gray-400 dark:hover:border-gray-300">
            2022
        </button>

        <button class="flex items-center h-12 px-4 py-2 md:text-sm text-xs font-bold text-center text-blue-600 border border-b-0 border-gray-300 sm:text-base dark:border-gray-500 rounded-t-md dark:text-white whitespace-nowrap focus:outline-none">
            2021
        </button>

        <button class="flex items-center h-12 px-4 py-2 md:text-sm text-xs  text-center text-gray-700 bg-transparent sm:text-base dark:border-gray-500 dark:text-white whitespace-nowrap cursor-base focus:outline-none hover:border-gray-400 dark:hover:border-gray-300">
            2020
        </button>

        <button class="flex items-center h-12 px-4 py-2 md:text-sm text-xs text-center text-gray-700 bg-transparent sm:text-base dark:border-gray-500 dark:text-white whitespace-nowrap cursor-base focus:outline-none hover:border-gray-400 dark:hover:border-gray-300">
            Previous Year
        </button>
    </div>
    <div class="lg:h-[600px] border lg:flex py-4">
        <div class="lg:h-full h-[600px] block lg:w-1/2 border-0 lg:border-r-2 px-4">
            <h1 class="text-2xl text-blue-600 font-bold underline">News</h1>
            <div class="h-full py-4">
                <div class="w-full md:h-28 md:flex shadow-md border">
                   <img src="../assets/img_caroussel/img_caroussel3.jpg" class="md:w-32 md:h-full object-cover w-full h-24" alt="">
                   <div class="p-2 text-center md:text-left">
                       <h3 class="text-md">Lorem, ipsum dolor sit amet consectetur</h3>
                       <p class="text-sm font-light mt-2">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aliquid laborum maxime illo quis at officiis suscipit</p>
                       <a href="#" class="text-sm text-blue-600 mt-2 hover:underline">Read More</a>
                   </div>
                   <div class="px-1 h-full bg-gray-400 w-1 md:block hidden">&nbsp;</div>
                </div>   
            </div>
        </div>
        <div class="lg:h-full h-[600px] block lg:w-1/2 px-4">
            <h1 class="text-2xl text-blue-600 font-bold underline">Events</h1>
            <div class="h-full py-4">
               <div class="w-full md:h-28 md:flex shadow-md border">
                   <img src="../assets/img_caroussel/img_caroussel3.jpg" class="md:w-32 md:h-full object-cover w-full h-24" alt="">
                   <div class="p-2 text-center md:text-left">
                       <h3 class="text-md">Lorem, ipsum dolor sit amet consectetur</h3>
                       <p class="text-sm font-light mt-2">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aliquid laborum maxime illo quis at officiis suscipit</p>
                       <a href="#" class="text-sm text-blue-600 mt-2">Read More</a>
                   </div>
                   <div class="px-1 h-full bg-gray-400 w-1 md:block hidden">&nbsp;</div>
                </div> 
            </div>
        </div>
    </div>
    </div>
<Footer/>
</template>