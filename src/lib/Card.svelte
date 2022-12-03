<script>
    import { Card, ToolbarButton, Dropdown, DropdownItem, Avatar, Button } from "flowbite-svelte";
</script>

<Card padding='sm' size="lg">
    <div class="flex flex-col items-center pb-4">
      <Avatar size="lg" src="/images/profile-picture-3.webp" />
        <h5 class="mb-1 text-xl font-medium text-gray-900 dark:text-white">Bonnie Green</h5>
        <span class="text-sm text-gray-500 dark:text-gray-400">Visual Designer</span>
        <div class="flex mt-4 space-x-3 lg:mt-6">
          <Button>Add friend</Button>
          <Button color="light" class="dark:text-white">Message</Button>
        </div>
    </div>
  </Card>