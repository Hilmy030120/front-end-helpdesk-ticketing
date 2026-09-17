<script setup>
import Sidebar from '@/components/admin/Sidebar.vue'
import Navbar from '@/components/app/Navbar.vue'
</script>

<template>
    <div class="flex h-screen">
        <!-- Sidebar -->
        <Sidebar />

        <!-- Main Content -->
        <main class="flex-1 overflow-x-hidden overflow-y-auto">
            <!-- Topbar -->
            <Navbar />

            <!-- Content -->
            <div class="p-6 space-y-6">
                <router-view></router-view>
            </div>
        </main>
    </div>
</template>