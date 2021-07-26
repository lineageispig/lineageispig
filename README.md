- 👋 Hi, I’m @lineageispig
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

---
title: "Hypothesis Testing in R"
output: html_notebook
---

```{r}
# generate random population
population <- rnorm(300, mean=65, sd=3.5)

# calculate population mean here:
population_mean <- mean(population)
population_mean
```

```{r}
# generate sample 1
sample_1 <- sample(population, size=30)
sample_1

# calculate sample 1 mean
sample_1_mean <- mean(sample_1)
sample_1_mean
```

```{r}
# generate samples 2,3,4 and 5
sample_2 <- sample(population, size=30)
sample_3 <- sample(population, size=30)
sample_4 <- sample(population, size=30)
sample_5 <- sample(population, size=30)
```

```{r}
# calculate sample means here:
sample_2_mean <- "Not calculated"
sample_2_mean
sample_3_mean <- "Not calculated"
sample_3_mean
sample_4_mean <- "Not calculated"
sample_4_mean
sample_5_mean <- "Not calculated"
sample_5_mean
```


<!---
lineageispig/lineageispig is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
