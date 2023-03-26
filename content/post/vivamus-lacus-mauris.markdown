+++
date = "2013-06-17T12:00:00-00:00"
title = "Vivamus Lacus Mauris"
output = "html_document"
+++

สวัสดีครับผมภัคพล

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Impedit, rerum voluptates veniam. Esse, nihil, ea, eaque, quos cum id tempore voluptate nisi nemo debitis impedit officiis culpa repellat voluptatum in aperiam error quo minima ratione ex pariatur maxime eligendi dolore nesciunt molestiae enim alias atque commodi delectus perferendis. Blanditiis, iste placeat nostrum in! Eligendi, omnis, unde, quos ullam nesciunt molestias quis a saepe nisi distinctio molestiae voluptate obcaecati officiis consequuntur similique aspernatur rerum sequi placeat iure quaerat itaque libero officia recusandae ad corrupti aperiam cum beatae. Adipisci ad natus deleniti.


```r
print("Hello Rmarkdown")
```

```
## [1] "Hello Rmarkdown"
```

```r
print("นี่คือบล็อกแรกของผม")
```

```
## [1] "นี่คือบล็อกแรกของผม"
```


```r
x <- c(1,2,3,4,5) 
y <- c(1,2,3,4,5)
data <- data.frame(x,y)

summary(lm(y~x , data))
```

```
## Warning in summary.lm(lm(y ~ x, data)): essentially perfect fit: summary may be
## unreliable
```

```
## 
## Call:
## lm(formula = y ~ x, data = data)
## 
## Residuals:
##          1          2          3          4          5 
##  8.890e-17 -1.876e-16  6.568e-17  7.592e-17 -4.287e-17 
## 
## Coefficients:
##              Estimate Std. Error   t value Pr(>|t|)    
## (Intercept) 0.000e+00  1.420e-16 0.000e+00        1    
## x           1.000e+00  4.283e-17 2.335e+16   <2e-16 ***
## ---
## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
## 
## Residual standard error: 1.354e-16 on 3 degrees of freedom
## Multiple R-squared:      1,	Adjusted R-squared:      1 
## F-statistic: 5.452e+32 on 1 and 3 DF,  p-value: < 2.2e-16
```

```r
plot(x,y)
```

<img src="/post/vivamus-lacus-mauris_files/figure-html/unnamed-chunk-2-1.png" width="672" />

Dolores harum alias consequatur blanditiis. Inventore, quod, ullam veritatis eum ratione neque quis fugit quae optio facilis in ipsa! Maiores, quia, possimus repellendus iusto nostrum nisi doloribus qui excepturi ducimus veritatis molestiae autem consequatur quae ex nihil id sapiente minima adipisci. Quibusdam, aperiam, sapiente, nobis, possimus vero laudantium delectus esse minus quo nihil perspiciatis accusamus. Cupiditate sapiente illum accusantium animi pariatur sed minima nam.

Harum, consectetur, quia nisi fugiat quasi ea amet cum inventore aperiam optio qui perspiciatis debitis molestiae laborum minima doloremque ullam eum nesciunt repellendus dolor dicta cumque deserunt. Quaerat, saepe, maxime, quod, dolor nisi assumenda aut est quos optio animi aliquid quidem voluptates adipisci hic recusandae dicta quis eligendi illo ducimus asperiores reiciendis odit distinctio natus? In, reprehenderit, facere, ipsam, vel architecto autem temporibus a quidem voluptatum at nesciunt quas facilis. Soluta, excepturi, nihil, illum dicta hic ratione tenetur voluptate dolorum a tempore dignissimos reprehenderit voluptas expedita officiis enim minus adipisci?

