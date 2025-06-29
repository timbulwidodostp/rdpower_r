# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Power Calculations for RD (Regression Discontinuity) Designs Use rdmde And rdpower With (In) R Software
install.packages("rdpower")
library("rdpower")
rdpower_r = read.csv("https://raw.githubusercontent.com/timbulwidodostp/rdpower_r/main/rdpower_r/rdpower_r.csv",sep = ";")
# Estimation Power Calculations for RD (Regression Discontinuity) Designs Use rdmde And rdpower With (In) R Software
# Minimum Detectable Effect calculation for Regression Discontinuity designs using robust bias-corrected local polynomial inference
rdmde <- rdmde(data = cbind(rdpower_r$demvoteshfor2, rdpower_r$demmv))
# Power calculations for Regression Discontinuity designs using robust bias-corrected local polynomial inference
rdpower <- rdpower(data = cbind(rdpower_r$demvoteshfor2, rdpower_r$demmv))
# Power Calculations for RD (Regression Discontinuity) Designs Use rdmde And rdpower With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished