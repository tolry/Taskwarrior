# Taskwarrior

```php
$tw = new \DavidBadura\Taskwarrior\Taskwarrior();

$task = new \DavidBadura\Taskwarrior\Task();
$task->addTag('home');

$tw->save($task);

$tasks = $tw->filter('+home');
```
