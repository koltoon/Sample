### Добро пожаловать

```scala
  def whileAlive: Duration.Inf(daysLeft: Int) = {
    val daysOfLife = for(day <- daysLeft; if (day isBad)) yield day make Good
    daysOfLife foreach ( print)
  }
```
