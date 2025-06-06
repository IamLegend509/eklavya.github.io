---
layout: page
title: Task 6
description: A lone Path in the FOrce
importance: 7
---

## Choose any one

**Points for any one Task: 100**

<a href="#" onclick="event.preventDefault(); redirectToTask('task6_1')">The Jedi CAD Academy</a>
<br>
<a href="#" onclick="event.preventDefault(); redirectToTask('task6_2')">The Galactic Signal Jam</a>
<br>
<a href="#" onclick="event.preventDefault(); redirectToTask('task6_3')">The HDL Order</a>

{% raw %}
<script>
function redirectToTask(taskId) {
  window.location.href = '/tasks/' + taskId;
}
</script>
{% endraw %}
