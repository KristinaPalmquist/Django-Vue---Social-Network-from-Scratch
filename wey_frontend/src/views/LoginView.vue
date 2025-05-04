<template>

    <div class="max-w-7xl mx-auto grid grid-cols-2 gap-4">
        <div class="main-left col-span-1">
            <div class="bg-white p-12 border border-gray-200 rounded-lg">
                <h1 class="mb-6 text-2xl">Log in</h1>
                <p class="mb-6 text-gray-500">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam,
                    accusamus ipsa, ducimus eveniet asperiores, mollitia consequuntur rerum fugiat voluptates neque ea
                    dolore! Corrupti, sunt rerum.
                </p>
                <p class="font-bold">
                    Don't have an account?
                    <RouterLink to="/signup" class="underline">Click here</RouterLink> to create one!
                </p>
            </div>
        </div>
        <div class="main-right col-span-1">
            <div class="bg-white p-12 border border-gray-200 rounded-lg">
                <form class="space-y-6">

                    <div>
                        <label for="email">Email</label>
                        <br>
                        <input type="email" placeholder="Your e-mail address"
                            class="w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg placeholder-gray-400"
                            id="email">
                    </div>
                    <div>
                        <label for="password">Password</label>
                        <br>
                        <input type="password" placeholder="Your password"
                            class="w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg placeholder-gray-400"
                            id="password">
                    </div>


                    <div><button class="py-4 px-6 bg-purple-600 text-white rounded-lg">Log in</button></div>
                </form>
            </div>
        </div>
    </div>
</template>