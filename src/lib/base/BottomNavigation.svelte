<script>
    import { BottomNav, BottomNavItem } from 'flowbite-svelte'
    import { HomeSolid, TableRowSolid, RectangleListSolid, UserCircleSolid } from 'flowbite-svelte-icons'
</script>

<BottomNav position="fixed" class="z-10" classInner="grid-cols-4" activeUrl="/">
    <BottomNavItem btnName="ホーム" href="/">
        <HomeSolid class="w-6 h-6 mb-1 text-gray-500 dark:text-gray-400 group-hover:text-primary-600 dark:group-hover:text-primary-500"/>
    </BottomNavItem>  
    <BottomNavItem btnName="時間割" href="/timetable">
        <TableRowSolid class="w-6 h-6 mb-1 text-gray-500 dark:text-gray-400 group-hover:text-primary-600 dark:group-hover:text-primary-500"/>
    </BottomNavItem>
    <BottomNavItem btnName="ToDo" href="/todo">
        <RectangleListSolid class="w-6 h-6 mb-1 text-gray-500 dark:text-gray-400 group-hover:text-primary-600 dark:group-hover:text-primary-500"/>
    </BottomNavItem>
    <BottomNavItem btnName="me" href="/me">
        <UserCircleSolid class="w-6 h-6 mb-1 text-gray-500 dark:text-gray-400 group-hover:text-primary-600 dark:group-hover:text-primary-500"/>
    </BottomNavItem>
</BottomNav>
