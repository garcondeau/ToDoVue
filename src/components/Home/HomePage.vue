<script setup lang="ts">
import ListItem from "../ListItem.vue";
import ToolingIcon from "../icons/IconTooling.vue";
import EcosystemIcon from "../icons/IconEcosystem.vue";
import SupportIcon from "../icons/IconSupport.vue";
import Container from "../Container.vue";
</script>

<template>
  <Container>
    <ListItem>
      <template #icon>
        <SupportIcon />
      </template>
      <template #heading>Organization</template>
      A ToDo app is designed to help users organize and manage their tasks in a
      way that allows them to keep track of what needs to be done, when it needs
      to be done, and how much progress they have made towards completing their
      tasks.
    </ListItem>

    <ListItem>
      <template #icon>
        <ToolingIcon />
      </template>
      <template #heading>Reminders and Notifications</template>
      A ToDo app can help users remember important tasks by sending
      notifications or reminders at a scheduled time or date. This can be useful
      for tasks that have specific deadlines or are easy to forget.
    </ListItem>

    <ListItem>
      <template #icon>
        <EcosystemIcon />
      </template>
      <template #heading>Collaboration</template>
      Some ToDo apps allow users to share tasks or projects with others, which
      can be helpful for individuals or teams working together on a project or
      for delegating tasks to others. This can also provide transparency and
      accountability in the completion of tasks.
    </ListItem>
  </Container>
</template>
