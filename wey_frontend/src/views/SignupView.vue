<template>

    <div class="max-w-7xl mx-auto grid grid-cols-2 gap-4">
        <div class="main-left col-span-1">
            <div class="bg-white p-12 border border-gray-200 rounded-lg">
                <h1 class="mb-6 text-2xl">Sign up</h1>
                <p class="mb-6 text-gray-500">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellendus, ex
                    quae sunt labore assumenda accusantium debitis autem incidunt eius neque nulla magni earum dolor
                    excepturi.
                </p>
                <p class="font-bold">
                    Already have an account?
                    <RouterLink to="/login" class="underline">Click here</RouterLink> to log in!
                </p>
            </div>
        </div>
        <div class="main-right col-span-1">
            <div class="bg-white p-12 border border-gray-200 rounded-lg">
                <form class="space-y-6">
                    <div>
                        <label for="name">Name</label>
                        <br>
                        <input type="name" placeholder="Your full name"
                            class="w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg placeholder-gray-400"
                            id="name">
                    </div>
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
                    <div>
                        <label for="repeat_password"> Repeat Password</label>
                        <br>
                        <input type="repeat_password" placeholder="Repeat your password"
                            class="w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg placeholder-gray-400"
                            id="password">
                    </div>

                    <div><button class="py-4 px-6 bg-purple-600 text-white rounded-lg">Sign up</button></div>
                </form>
            </div>
        </div>
    </div>
</template>