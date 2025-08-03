# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Logistic regression Cedergreen-Ritz-Streibig model Use CD_model (seedreg) With (In) R Software
install.packages("seedreg")
library("seedreg")
CD_model = read.csv("https://raw.githubusercontent.com/timbulwidodostp/CD_model/main/CD_model/CD_model.csv",sep = ";")
# Estimation Logistic regression Cedergreen-Ritz-Streibig model Use CD_model (seedreg) With (In) R Software
trat <- CD_model$trat
germ <- CD_model$germ
CD_model(trat, germ)
# Logistic regression Cedergreen-Ritz-Streibig model Use CD_model (seedreg) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished