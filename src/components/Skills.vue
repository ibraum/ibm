<script setup lang="ts">
import { faBitbucket, faBootstrap, faCss3Alt, faFigma, faGit, faGithub, faGitlab, faHtml5, faJs, faLaravel, faNodeJs, faPhp, faPython, faVuejs } from '@fortawesome/free-brands-svg-icons';
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';

    
</script>

<template>
    <div class="w-full min-h-[100vh] flex items-center justify-between relative overflow-hidden">

        <div class="absolute h-[400px] w-full bg-[linear-gradient(180deg,var(--color),transparent)] rounded-full blur-[50px] left-[0%] top-[-50px] opacity-[0.35]"></div>
        <div class="absolute h-[400px] w-full bg-[linear-gradient(0deg,var(--color),transparent)] rounded-full blur-[150px] left-[0%] bottom-[0px] opacity-[0.35]"></div>

        <div class="w-full min-h-[100vh] flex flex-col items-start px-[75px] z-1 pt-[50px]">
            <div class="bg-[linear-gradient(90deg,var(--color),white)] bg-clip-text text-transparent text-[2.5vw] font-bold">Skills</div>
            <div class="min-h-[80vh] w-full flex justify-between gap-2 flex-wrap mt-[25px]">
                <div class="relative w-[20%] grow-1 text-zinc-500 p-3 rounded bg-[linear-gradient(45deg,#1D1D1D,#090909,#1D1D1D,#090909,#1D1D1D)] hover:bg-[linear-gradient(45deg,#242424,#090909,#1D1D1D)] duration-200">
                    <div class="w-full h-full bg-[linear-gradient(45deg,var(--color))] opacity-[0.1] absolute top-0 left-0 z-0"></div>
                    <div class=" text-zinc-600 border border-0 border-b-1 border-zinc-800">frontend</div>
                    <div class="mt-3 w-full flex flex-wrap gap-1">
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-orange-500 hover:border-orange-500">
                            <FontAwesomeIcon :icon="faHtml5" class="text-[1.8vw]"/>
                            <div class="skills-percent w-full h-full bg-orange-500 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">90%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-blue-500 hover:border-blue-500">
                            <FontAwesomeIcon :icon="faCss3Alt" class="text-[1.8vw]"/>
                            <div class="skills-percent w-full h-full bg-blue-500 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">90%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-yellow-500 hover:border-yellow-500">
                            <FontAwesomeIcon :icon="faJs" class="text-[1.8vw]"/>
                            <div class="skills-percent w-full h-full bg-yellow-500 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">80%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-green-500 hover:border-green-500">
                            <FontAwesomeIcon :icon="faVuejs" class="text-[1.8vw]"/>
                            <div class="skills-percent w-full h-full bg-green-500 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">80%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-cyan-500 hover:border-cyan-500">
                            <div class="text-[1vw]">Tailwind</div>
                            <div class="skills-percent w-full h-full bg-cyan-500 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">75%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-purple-500 hover:border-purple-500">
                            <FontAwesomeIcon :icon="faBootstrap" class="text-[1.8vw]"/>
                            <div class="skills-percent w-full h-full bg-purple-500 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">70%</div>
                        </div>
                    </div>
                </div>
                <div class="relative w-[20%] grow-1 text-zinc-500 p-3 rounded bg-[linear-gradient(45deg,#1D1D1D,#090909,#1D1D1D,#090909,#1D1D1D)] hover:bg-[linear-gradient(45deg,#242424,#090909,#1D1D1D)] duration-200">
                    <div class="w-full h-full bg-[linear-gradient(45deg,var(--color))] opacity-[0.1] absolute top-0 left-0 z-0"></div>
                    <div class=" text-zinc-600 border border-0 border-b-1 border-zinc-800">backend</div>
                    <div class="mt-3 w-full flex flex-wrap gap-1">
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-purple-300 hover:border-purple-300">
                            <FontAwesomeIcon :icon="faPhp" class="text-[1.8vw]"/>
                            <div class="skills-percent w-full h-full bg-purple-300 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">70%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-green-600 hover:border-green-600">
                            <FontAwesomeIcon :icon="faNodeJs" class="text-[1.8vw]"/>
                            <div class="skills-percent w-full h-full bg-green-600 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">60%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-red-500 hover:border-red-500">
                            <FontAwesomeIcon :icon="faLaravel" class="text-[1.8vw]"/>
                            <div class="skills-percent w-full h-full bg-red-500 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">85%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-yellow-400 hover:border-yellow-400">
                            <div class="text-[1vw]">Express JS</div>
                            <div class="skills-percent w-full h-full bg-yellow-400 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">60%</div>
                        </div>
                    </div>
                    <div class="mt-3 text-zinc-600 border border-0 border-b-1 border-zinc-800">data Science</div>
                    <div class="mt-3 w-full flex flex-wrap gap-1">
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-yellow-400 hover:border-yellow-400">
                            <FontAwesomeIcon :icon="faPython" class="text-[1.8vw]"/>
                            <div class="skills-percent w-full h-full bg-yellow-400 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">75%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-green-600 hover:border-green-600">
                            <div class="text-[1vw]">Panda</div>
                            <div class="skills-percent w-full h-full bg-green-600 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">60%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-green-600 hover:border-green-600">
                            <div class="text-[1vw]">Numpy</div>
                            <div class="skills-percent w-full h-full bg-green-600 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">60%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-green-600 hover:border-green-600">
                            <div class="text-[1vw]">Matplotlib</div>
                            <div class="skills-percent w-full h-full bg-green-600 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">60%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-green-600 hover:border-green-600">
                            <div class="text-[1vw]">Sql</div>
                            <div class="skills-percent w-full h-full bg-green-600 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">90%</div>
                        </div>
                    </div>
                </div>
                <div class="relative w-[20%] grow-1 text-zinc-500 p-3 rounded bg-[linear-gradient(45deg,#1D1D1D,#090909,#1D1D1D,#090909,#1D1D1D)] hover:bg-[linear-gradient(45deg,#242424,#090909,#1D1D1D)] duration-200">
                    <div class="w-full h-full bg-[linear-gradient(45deg,var(--color))] opacity-[0.1] absolute top-0 left-0 z-0"></div>
                    <div class=" text-zinc-600 border border-0 border-b-1 border-zinc-800">tools & versionning</div>
                    <div class="mt-3 w-full flex flex-wrap gap-1">
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-stone-400 hover:border-stone-400">
                            <FontAwesomeIcon :icon="faGithub" class="text-[1.8vw]"/>
                            <div class="skills-percent w-full h-full bg-stone-400 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">90%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-orange-400 hover:border-orange-400">
                            <FontAwesomeIcon :icon="faGitlab" class="text-[1.8vw]"/>
                            <div class="skills-percent w-full h-full bg-orange-400 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">60%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-blue-500 hover:border-blue-500">
                            <FontAwesomeIcon :icon="faBitbucket" class="text-[1.8vw]"/>
                            <div class="skills-percent w-full h-full bg-blue-500 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">50%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-orange-400 hover:border-orange-400">
                            <FontAwesomeIcon :icon="faGit" class="text-3xl"/>
                            <div class="skills-percent w-full h-full bg-orange-400 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">80%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-blue-400 hover:border-blue-400">
                            <div class="text-[1vw]">Vs Code</div>
                            <div class="skills-percent w-full h-full bg-blue-400 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">95%</div>
                        </div>
                    </div>
                </div>
                <div class="relative w-[20%] grow-1 text-zinc-500 p-3 rounded bg-[linear-gradient(45deg,#1D1D1D,#090909,#1D1D1D,#090909,#1D1D1D)] hover:bg-[linear-gradient(45deg,#242424,#090909,#1D1D1D)] duration-200">
                    <div class="w-full h-full bg-[linear-gradient(45deg,var(--color))] opacity-[0.1] absolute top-0 left-0 z-0"></div>
                    <div class=" text-zinc-600 border border-0 border-b-1 border-zinc-800">databases</div>
                    <div class="mt-3 w-full flex flex-wrap gap-1">
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-sky-900 hover:border-sky-900">
                            <div class="text-[1vw]">Mysql</div>
                            <div class="skills-percent w-full h-full bg-sky-900 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">90%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-green-900 hover:border-green-900">
                            <div class="text-[1vw]">MongoDB</div>
                            <div class="skills-percent w-full h-full bg-green-900 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">65%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-sky-900 hover:border-sky-900">
                            <div class="text-[1vw]">PostgreSQL</div>
                            <div class="skills-percent w-full h-full bg-sky-900 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">60%</div>
                        </div>
                    </div>
                    <div class="mt-3 text-zinc-600 border border-0 border-b-1 border-zinc-800">others</div>
                    <div class="mt-3 w-full flex flex-wrap gap-1">
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-pink-400 hover:border-pink-400">
                            <FontAwesomeIcon :icon="faFigma" class="text-[1.8vw]"/>
                            <div class="skills-percent w-full h-full bg-pink-400 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">80%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-blue-900 hover:border-blue-900">
                            <div class="text-[1vw]">Photoshop</div>
                            <div class="skills-percent w-full h-full bg-blue-900 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">75%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-orange-900 hover:border-orange-900">
                            <div class="text-[1vw]">Illustrator</div>
                            <div class="skills-percent w-full h-full bg-orange-900 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">75%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-sky-900 hover:border-sky-900">
                            <div class="text-[1vw]">Vercel</div>
                            <div class="skills-percent w-full h-full bg-sky-900 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">80%</div>
                        </div>
                        <div class="skills w-[calc(100%/3.1)] h-[75px] flex flex-col items-center justify-center z-2 border border-zinc-600/20 border-1 rounded hover:text-sky-900 hover:border-sky-900">
                            <div class="text-[1vw]">Netlify</div>
                            <div class="skills-percent w-full h-full bg-sky-900 text-xl text-black border border-2 border-black flex items-center justify-center rounded absolute top-0 left-0">60%</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="h-[200px] w-full bg-[linear-gradient(180deg,#000000,rgba(0,0,0,0))] absolute top-0 z-0"></div>
        <div class="h-[75px] w-full bg-[linear-gradient(0deg,#000000,rgba(0,0,0,0))] absolute bottom-0 z-0"></div>
    </div>
</template>

<style scoped>
    .skills {
        position: relative;
        overflow: hidden;
    }

    .skills-percent {
        transform: translateY(100%);
        transition: all .3s ease-in-out .1s;
    }

    .skills:hover .skills-percent {
        transform: translateY(0);
    }
</style>