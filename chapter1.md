---
title: 'Setup RStudio'
description: 'Chapter description goes here.'
---

## Insert exercise title here

```yaml
type: NormalExercise
key: 7683200cc3
xp: 100
```

context blablba
more context blablba

`@instructions`
- instructions
- instructions 2
- instructions 3
- instructions 4

`@hint`


`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}

```

`@solution`
```{r}
version$version.string
```

`@sct`
```{r}
ex() %>% 
    check_code('(\\[1\\]){0,1}[:space:]*(\\")*(R version ){0,1}3\\.[5-9]\\.[2-0]', fixed = TRUE)


success_msg("That looked really good!", TRUE)
```
