<template>
    <div>
        <header>
            <nav>
                <NuxtLink to="/"></NuxtLink>
                <ul>
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/gunplas">Gunplas</NuxtLink></li>
                </ul>
            </nav>
        </header>

        <div>
            <slot/>
        </div>
    </div>
</template>