# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Firth's (Firth) Bias-Reduced Logistic Regression Use logistf With (In) R Software
install.packages("logistf")
library("logistf")
logistf = read.csv("https://raw.githubusercontent.com/timbulwidodostp/logistf/main/logistf/logistf.csv",sep = ";")
# Estimation Firth's (Firth) Bias-Reduced Logistic Regression Use logistf With (In) R Software
logistf <- logistf(formula = case ~ age + oc + vic + vicl + vis + dia, data = logistf)
summary(logistf)
# Firth's (Firth) Bias-Reduced Logistic Regression Use logistf With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished