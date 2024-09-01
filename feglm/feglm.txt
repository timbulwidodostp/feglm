# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fixed-effects GLM (General Linear Model) estimations Use feglm With (In) R Software
install.packages("fixest")
library("fixest")
feglm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/feglm/main/feglm/feglm.csv",sep = ";")
# Estimation Fixed-effects GLM (General Linear Model) estimations Use feglm With (In) R Software
feglm = feglm(Dependen ~ Independen_1 + Independen_2 + Independen_3 | Fixed_Effect, feglm)
summary(feglm)
# Fixed-effects GLM (General Linear Model) estimations Use feglm With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished