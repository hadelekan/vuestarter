<template>
  <aside class="sidebar">
            <div class="sidebar__menu-group">
                <ul class="sidebar_nav">
                    <li class="menu-title">
                        <span>Main menu</span>
                    </li>
                    <li class="">
                        <a href="dashboard.html" class="active">
                            <span data-feather="home" class="nav-icon"></span>
                            <span class="menu-text">Dashboard</span>
                        </a>
                    </li>
                    <li class="has-child">
                        <a href="#" class="">
                            <span data-feather="layout" class="nav-icon"></span>
                            <span class="menu-text">Subjects</span>
                            <span class="toggle-icon"></span>
                        </a>
                        <ul>
                            <li>
                                <a href="subjects.html#primary" class="">Primary</a>
                            </li>
                            <li>
                                <a href="subjects.html#junior" >Junior Secondary</a>
                            </li>
                            <li>
                                <a href="subjects.html#senior" class="">Senior Primary </a>
                            </li>
                        </ul>
                    </li>
                    <li class="has-child">
                        <a href="#" class="">
                            <span data-feather="folder" class="nav-icon"></span>
                            <span class="menu-text"> Users </span>
                            <span class="toggle-icon"></span>
                        </a>
                        <ul>
                            <li>
                                <a href="users-card.html" class="">Students</a>
                            </li>
                            <li>
                                <a href="users-card2.html" class=""> Guardians </a>
                            </li>
                        </ul>
                    </li>
                    <li class="menu-title m-top-30">
                        <span>Applications</span>
                    </li>
                 
                    <li class="has-child">
                        <a href="#" class="">
                            <span data-feather="message-square" class="nav-icon"></span>
                            <span class="menu-text">Officers</span>
                            <span class="toggle-icon"></span>
                        </a>
                        <ul>
                            <li>
                                <a class="" href="view-Officers.html">View</a>
                            </li>
                        </ul>
                    </li>
                  
                    <li class="has-child">
                        <a href="#" class="">
                            <span data-feather="grid" class="nav-icon"></span>
                            <span class="menu-text">Subjects</span>
                            <span class="toggle-icon"></span>
                        </a>
                        <ul>
                            <li>
                                <a href="feather.html" class="">View</a>
                            </li>
                            <li>
                                <a href="fontawesome.html" class="">Add New</a>
                            </li>
                        </ul>
                    </li>
                
                </ul>
            </div>
        </aside>
</template>

<script>
export default {

}
</script>

<style>

</style>