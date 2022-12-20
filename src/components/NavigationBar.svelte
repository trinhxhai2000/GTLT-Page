<script lang="ts">
    import { onMount } from "svelte";
    import logo from "../images/menu-logo.png";
</script>

<div class="nav-wrapper">
    <nav id="ttr_menu" class="navbar-default navbar">
        <div id="ttr_menu_inner_in">
            <div class="menuforeground" />
            <div id="navigationmenu">
                <div class="navbar-header">
                    <button
                        id="nav-expander"
                        data-target=".navbar-collapse"
                        data-toggle="collapse"
                        class="navbar-toggle"
                        type="button"
                    >
                        <span class="sr-only" />
                        <span class="icon-bar" />
                        <span class="icon-bar" />
                        <span class="icon-bar" />
                    </button>

                    <img id="nav-logo" class="ttr_menu_logo" src={logo} />
                </div>
                <div class="menu-center collapse navbar-collapse">
                    <ul class="ttr_menu_items nav navbar-nav navbar-right">
                        <li class="ttr_menu_items_parent dropdown active">
                            <a
                                href="index.html"
                                class="ttr_menu_items_parent_link_active"
                                ><span class="menuchildicon" />Trang chủ</a
                            >
                            <hr class="horiz_separator" />
                        </li>
                        <li class="ttr_menu_items_parent dropdown">
                            <a
                                href="/GTLT-Page/about"
                                class="ttr_menu_items_parent_link"
                                ><span class="menuchildicon" />Giới thiệu</a
                            >
                            <hr class="horiz_separator" />
                        </li>

                        <li class="ttr_menu_items_parent dropdown">
                            <a
                                href="halloffame.html"
                                class="ttr_menu_items_parent_link"
                                ><span class="menuchildicon" />Thành tựu</a
                            >
                            <hr class="horiz_separator" />
                        </li>
                        <li class="ttr_menu_items_parent dropdown">
                            <a
                                href="contact.html"
                                class="ttr_menu_items_parent_link"
                                ><span class="menuchildicon" />Liên hệ</a
                            >
                            <hr class="horiz_separator" />
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </nav>
</div>

<style lang="scss">
    #nav-logo {
        /* border: 2px solid red; */
        height: 55px;
        width: 55px;
    }
</style>
