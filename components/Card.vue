<template>
    <div class="rounded overflow-hidden shadow-lg flex flex-row">
        <Logo/>
        <div class="px-6 py-4">
            <Title />
            <SubTitle />
            <hr class="w-1/5 my-4 border-2">
            <Description />
            <Links />
        </div>
    </div>
</template>

<script>
    import Logo from "@/components/Logo"
    import Title from "@/components/Title"
    import SubTitle from "@/components/SubTitle"
    import Description from "@/components/Description"
    import Links from "@/components/Links"

    export default {
        name: 'Card',
        components: {
            Logo,
            Title,
            SubTitle,
            Description,
            Links
        }
    }

</script>
