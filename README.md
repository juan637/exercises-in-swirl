# exercises-in-swirl
three first practical exercises in swirl

install.packages("swirl")
install_from_swirl("R Programming")
ls
ls()
rm(list=ls())
swirl()
Persistencia

1
1
1
5+7
x<-5+7
x
y<-x-3
y
z<-c(1.1,9,3.14)
z?c
z
a<-555
c(z,555,z)
z*2+1000
my_sqrt<-sqrt(z-1)
1
my_sqrt
my_div <- z/my_sqrt
1
print(my_div)
my_div
c(1,2,3,4)+c(0,10)
c(1,2,3,4)+c(0,100,100)

my_div
1
juancamiloparraaguirre@hotmail.com
PVLprF5ckSDLy8WV
0
swirl

library(swirl)
rm(list=ls())
swirl()
persistencia
1
2
getwd()
ls()
x<-9
ls()
list.files()
?list.files
args(list.files)
old.dir<-getwd()
dir.create("testdir")
setwd("testdir")
file.create("mytest.R")
list.files()
file.exists("mytest.R")
file.info("mytest.R")
file.rename("mytest2.R")
file.rename("mytest.R","mytest2.R")
file.remove("mytest2.R")
file.copy("mytest2.R","mytest3.R")
file.path("mytest3.R")
file.path("folder1","folder2")
?dir.create
dir.create("testdir2")
info()
skip()
unlink("testdir2",recursive=TRUE)
setwd()
old.dir
setwd(old.dir)
unlink("testdir",recursive=TRUE)
1
juancamiloparraaguirre@hotmail.com
sUi7Sz1RIM1P7lxe
1
3
1:20
pi:10
15:1
?":"
seq()
seq(1,20)
seq(0,10,by=0.5)
my_seq<-seq(5,10,length=30)
length(my_seq)
1:30
1:length(my_seq)
seq(along.with=my_seq)
seq_along(my_seq)
rep(0,times=40)
rep(c(0,1,2),times=10)
rep(c(0,1,2),each=10)
2
juancamiloparraaguirre@hotmail.com
cQVQUuKksA467niZ
0

swirl()
persistencia
1
