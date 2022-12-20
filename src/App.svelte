<script lang="ts">
    import { Router, Route } from "svelte-routing";
    import NavigationBar from "./components/NavigationBar.svelte";
    import About from "./pages/About.svelte";
    import Home from "./pages/Home.svelte";
</script>

<Router url="" basepath="/GTLT-Page/">
    <NavigationBar />

    <Route path="/">
        <Home />
    </Route>

    <Route path="/about">
        <About />
    </Route>
</Router>

<style>
</style>
