<template>
    <div id="main">
        <Header title="喵喵影院"></Header>
        <div id="content">
            <CiMenu></CiMenu>
            <CiList></CiList>
        </div>
        <TabBar></TabBar>
    </div>
</template>

<script>
    import Header from "@/components/Header"
    import TabBar from "@/components/TabBar"
    import CiList from "@/components/CiList"
    import CiMenu from "@/components/CiMenu"

    export default {
        name: "Cinema",
        components:{
            Header,
            TabBar,
            CiList,
            CiMenu
        }
    }
</script>

<style scoped>


</style>