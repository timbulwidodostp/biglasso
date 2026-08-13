# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit lasso penalized regression path for big data Use biglasso With (In) R Software
install.packages("biglasso")
library("biglasso")
# Estimation Fit lasso penalized regression path for big data Use biglasso With (In) R Software
biglasso = read.csv("https://raw.githubusercontent.com/timbulwidodostp/biglasso/main/biglasso/biglasso.csv",sep = ";")
X <- cbind(biglasso$X_1, biglasso$X_2, biglasso$X_3)
y <- biglasso$Y
X.bm <- as.big.matrix(X)
biglasso <- biglasso(X.bm, y)
plot(biglasso)
# Fit lasso penalized regression path for big data Use biglasso With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished