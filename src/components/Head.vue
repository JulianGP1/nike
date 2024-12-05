<script>
import BlockInvi from './BlockInvi.vue';
export default {
  components: {
    BlockInvi,
  },
};
</script>
<template>

    <!-- superior -->
    <div class="bg-[#F7F7F7] w-screen h-10 flex  items-center px-[5%] justify-between">
        <div class="flex w-20 justify-between">
            <svg xmlns="http://www.w3.org/2000/svg" class="cursor-pointer" width="24" height="24" viewBox="0 0 24 24">
                <path fill="currentColor"
                    d="M13.55 2.194v-.075q0-.525.338-.938q.337-.412.862-.412c.525 0 .663.112.938.337s.425.525.45.9q.037.563-.338.938c-.375.375-.55.375-.9.375l-.225.075l.075.112l-.075.413l-.15 1.2q.075.075.075.15l-.15.75q-.075.15-.15.225l-.075.3a23 23 0 0 1-.45 1.575v.15q-.075.375-.112.6t-.263.75q-.15.3 0 .975l.075.075q0 .225.188.525c.188.3.187.375.187.525q.075 1.5-.225 2.55l.15.45q.9.45.525.975l.375.15q.9.45 1.275.787q.375.338.75.713q.3.075.45.225l.225.075q1.575 1.05 3.15 2.55l.3.225v.075l-.075.15l.225.15h.075q.225.15.3.15h.075q.075 0 .15-.075l.15-.075q.15-.15.3-.225h.3q.075 0 0 .075l-.3.15l-.375.45h.525l.525.075q.225-.075.375-.15l.375-.225q.225-.075.45.15h.075q.075.075-.075.225l-.9.825q-.375.3-.675.375l-.975.675q-.075.075-.15 0l-.225-.3l-.15-.3l-.188-.263l-.225-.3l-.187-.225l-.15-.187l-.3-.225q-.15 0-.3-.075l-.975-.75q-.225 0-.525-.225q-1.125-.975-1.5-1.2l-.45-.3l-.9-.15q-.45-.075-1.2-.45l-.6-.3q-.6-.3-.825-.3l-.3-.15q-.3-.075-.45-.15l-.15-.15q-.15 0-.3.075l-1.5.75l-1.875.825q-.75.6-1.425.975l-.825.375l-1.275.9q-.15.15-.3 0l-.15.15q-.225.075-.3.075l-.3.15v.15H3.2l-.15.225q-.15.3-.3.337t-.187.113a.4.4 0 0 1-.075.112l-.15.15l-.225.15l-.338-.037l-.45.075l-.3.075q-.375.075-.6-.113q-.225-.187-.375-.562q-.15-.225.15-.375l.075-.075q.075-.075.225-.075h.45l.6-.225l.3-.075q0-.15.075-.225t.225-.075v-.075a.7.7 0 0 1-.075-.3q-.076-.15-.037-.225q.037-.075.075-.075h.037l.075.225q.075.375.225.225l.075-.15q.075-.15.225-.15l.15.15l.15-.15l-.075-.075q0-.075.075-.075l.3-.3q.375-.45.9-.825q1.05-.825 2.25-1.275q.375-.375.825-.375q.3-.525.9-1.125q.525-.375.75-.525q.15-.3.375-.3h.075l.15-.15q.15-.075.225-.15v-.375q0-.375.075-.6t.375-.225l.3-.3q-.15-.3-.15-.675h-.075q-.15-.225-.15-.45q-.225-.375-.3-.6H9.65q-.075.225-.375.3l-.075.15q-.3.525-.525.787q-.225.263-.825.638q-.375.375-.525.825q-.075.225 0 .45l-.075.15h.075q0 .15.075.15h.075q.15.075.15.187c0 .112-.075.1-.225.075a.6.6 0 0 1-.337-.15q-.113-.112-.188-.112l-.225.225q-.15.225-.3.187q-.15-.037-.075-.112l.075-.075q.075-.15 0-.15l-.6.15q-.075.075-.187 0c-.112-.075-.063-.1.037-.15l.375-.15q0-.075-.075-.075q-.3.15-.6.075l-.375-.075l-.075-.075q0-.075.075-.075q.3.075.75-.075l.525-.225l.6-.675l.075-.15q.3-.6.638-1.088a3.7 3.7 0 0 1 .712-.787l.075-.3q.15-.3.3-.525t.375-.6l.225-.3q.3-.45.675-.45l.225-.225q.075-.075.075-.225l.15-.15l-.075-.075q-.45-.375-.45-.675q-.075-.525.338-.9c.413-.375.55-.363.825-.338q.412.038.637.263l.15.15q.075 0 .075.075l.3.15v.225q.15.15.15.225q.15-.225.45-.525l.375-1.2q0-.3.15-.6l.15-.225v-.15l.225-.9h.15l.225-.9a.93.93 0 0 0 0-.525l-.3-.75z" />
            </svg>
            <svg xmlns="http://www.w3.org/2000/svg" class="cursor-pointer" width="24" height="24" viewBox="0 0 512 512">
                <path fill="currentColor"
                    d="M42.63 89c8.3 49.2 17.42 100.1 14.35 151.5c-2.9 48.8-28.19 92.8-31.58 134.5h319.7c5.3-16.4 16.2-30.9 28.3-42.1c4.2-3.9 8.5-7.5 12.8-10.6c-34.9-9.7-61.7-24-82.5-41.3H244v-18h41c-8.5-9.5-15.7-19.6-21.7-30H208v-18h46c-4.6-9.9-8.4-19.9-11.7-30H192v-18h44.8c-2.8-10.1-5.3-20.2-7.6-30H176v-18h49c-2.4-10.5-4.9-20.54-7.7-30zM128 215c31.4 0 57 25.6 57 57s-25.6 57-57 57c-31.37 0-57-25.6-57-57s25.63-57 57-57m0 18c-21.6 0-39 17.4-39 39s17.4 39 39 39s39-17.4 39-39s-17.4-39-39-39m287.6 96c-5 .3-18.6 6.5-30 17.1c-8.7 8-16.5 18.3-21.2 28.9H448c11.5 0 25.6-5.7 38.6-12.3c-.4-4.2-1-7.7-2.2-10c-1.6-3.3-3.9-5.7-8.7-8.3c-9.6-5.2-28.9-9.5-60.1-15.4m71.4 52.9c-2 .9-3.4 1.6-5.7 2.5C471 388.5 459 393 448 393H25v30h407c22.2 0 45.3-8.7 55-12.8z" />
            </svg>
        </div>

        <ul class="list-none flex  gap-4   space-x-2">
            <li class="border-r border-black border-collapse pr-2 cursor-pointer">
                Buscar una tienda
            </li>
            <li class="border-r border-black pr-2 cursor-pointer">
                Ayuda
            </li>
            <li class="border-r border-black pr-2 cursor-pointer">
                Unete a nosotros
            </li>
            <li class="cursor-pointer" >
                Iniciar Sesion
            </li>
        </ul>
    </div>
    <!-- abajo -->
    <div class="h-25 w-screen  bg-white flex items-center justify-between px-[5%]">
        <svg xmlns="http://www.w3.org/2000/svg" width="70" height="70" viewBox="0 0 24 24">
            <path fill="currentColor" fill-rule="evenodd"
                d="M5.243 8.375c-1.168 1.334-2.785 2.828-3.173 4.692c-.612 2.938 2.962 2.858 4.697 2.141c5.105-2.11 10.155-4.353 15.233-6.53c-4.937 1.315-9.857 2.699-14.812 3.945c-3.545.892-2.855-2.272-1.945-4.248"
                clip-rule="evenodd" />
        </svg>
        <ul class="gap-4 relative flex list-none items-center font-mono text-[17px]">
    <li class="group relative">Novedades y destacados
        <div class="w-full bg-black h-1 hidden group-hover:block"></div>
        <BlockInvi class="hidden group-hover:block fixed  left-0 w-screen" />
    </li>
    <li class="group relative">Hombre
        <div class="w-full bg-black h-1 hidden group-hover:block"></div>
        <BlockInvi class="hidden group-hover:block fixed  left-0 w-screen" />
    </li>
    <li class="group relative">Mujer
        <div class="w-full bg-black h-1 hidden group-hover:block"></div>
        <BlockInvi class="hidden group-hover:block fixed  left-0 w-screen" />
    </li>
    <li class="group relative">Niño/a
        <div class="w-full bg-black h-1 hidden group-hover:block"></div>
        <BlockInvi class="hidden group-hover:block fixed  left-0 w-screen" />
    </li>
    <li class="group relative">Ofertas
        <div class="w-full bg-black h-1 hidden group-hover:block"></div>
        <BlockInvi class="hidden group-hover:block fixed  left-0 w-screen" />
    </li>
    <li>
        
    </li>
</ul>



        <div class=" flex items-center w-40  h-8 bg-gray-200 rounded-3xl ">
            <div class="pl-2 cursor-pointer rounded-3xl hover:bg-gray-300">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-7 " viewBox="0 0 256 256">
                <g fill="currentColor">
                    <path d="M192 112a80 80 0 1 1-80-80a80 80 0 0 1 80 80" opacity="0.2" />
                    <path
                        d="m229.66 218.34l-50.06-50.06a88.21 88.21 0 1 0-11.32 11.31l50.06 50.07a8 8 0 0 0 11.32-11.32M40 112a72 72 0 1 1 72 72a72.08 72.08 0 0 1-72-72" />
                </g>
            </svg>
           </div>
            <input type="text" class=" bg-transparent   hover:bg-gray-100 w-28 hover:rounded-3xl placeholder:font-bold pl-4" placeholder="Buscar">

        </div>



        <div class="flex w-16 justify-between   ">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
            <path fill="currentColor"
                d="m12.1 18.55l-.1.1l-.11-.1C7.14 14.24 4 11.39 4 8.5C4 6.5 5.5 5 7.5 5c1.54 0 3.04 1 3.57 2.36h1.86C13.46 6 14.96 5 16.5 5c2 0 3.5 1.5 3.5 3.5c0 2.89-3.14 5.74-7.9 10.05M16.5 3c-1.74 0-3.41.81-4.5 2.08C10.91 3.81 9.24 3 7.5 3C4.42 3 2 5.41 2 8.5c0 3.77 3.4 6.86 8.55 11.53L12 21.35l1.45-1.32C18.6 15.36 22 12.27 22 8.5C22 5.41 19.58 3 16.5 3" />
        </svg>
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-width="2"
                d="M4 7h16v16H4zm4 2V5c0-2.21 1.795-4 4-4h0c2.21 0 4 1.795 4 4v4" />
        </svg>
    </div>
    </div>
</template>