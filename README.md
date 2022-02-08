# week-3-a-mean
f <- function(n){
  sum <- 0
  for(x in n){
    sum <- sum+x
  }
  mean <- sum/length(n)
  return(mean)
}
n=scan()
mean=f(n)
print(mean)




OUTPUT:
> f<-function(n){
+   sum<-0
+   for(x in n){
+     sum<-sum+x
+   }
+   mean<-sum/length(n)
+   return (mean)
+ }
> n=scan()
1: 5
2: 7
3: 6
4: 4
5: 
Read 4 items
> mean=f(n)
> print(mean)
[1] 5.5
> 
