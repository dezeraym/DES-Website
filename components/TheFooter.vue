<template>
    <footer class="bg-blue">
        <div
            class="max-w-7xl mx-auto py-12 px-4 overflow-hidden sm:px-6 lg:px-8"
        >
            <nav
                class="-mx-5 -my-2 flex flex-wrap justify-center"
                aria-label="Footer"
            >
                <div class="px-5 py-2">
                    <NuxtLink
                        to="/board"
                        class="text-base hover:text-black text-grey-900"
                    >
                        Board
                    </NuxtLink>
                </div>

                <div class="px-5 py-2">
                    <NuxtLink
                        to="/become_a_member"
                        class="text-base hover:text-black text-grey-900"
                    >
                        Become a member
                    </NuxtLink>
                </div>

                <div class="px-5 py-2">
                    <a
                        href="https://docs.google.com/document/d/1i6oXabir-628csa2bQacHpc17Kmhec9EfkyHij9yQGM/edit#heading=h.sns5qzyi4gru"
                        class="text-base hover:text-black text-grey-900"
                    >
                        Bylaws
                    </a>
                </div>

                <div class="px-5 py-2">
                    <NuxtLink
                        to="/code_of_conduct"
                        class="text-base hover:text-black text-grey-900"
                    >
                        Code of Conduct
                    </NuxtLink>
                </div>

                <div class="px-5 py-2">
                    <NuxtLink
                        to="/sponsors"
                        class="text-base hover:text-black text-grey-900"
                    >
                        Sponsors
                    </NuxtLink>
                </div>

                <div class="px-5 py-2">
                    <NuxtLink
                        to="/contact"
                        class="text-base hover:text-black text-grey-900"
                    >
                        Contact
                    </NuxtLink>
                </div>
            </nav>
            <p class="mt-8 text-center text-base text-grey-700">
                Dev Edmonton Society
            </p>
        </div>
    </footer>
</template>

<style scoped>
.bg-blue {
    background-color: #d3deee;
}
</style>
