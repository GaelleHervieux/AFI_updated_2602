**plot_Colorado_evgam_extremes_1940-2025_CI.ipynb :**
<br>
<br>
Comparison of the Confidence Intervals computed by the simulate function provided by evgam (simulate) 
for the evgam GEV analyse and computed by pbooter a distillery bootstrap function for the extRemes GEV 
analyse (pbooter).<br>
Both methods are using a 1000 iterations.<br>
<br>
Evgam formula : list(AFI <br>
~ s(DJFtas,bs='cr',k=10)+s(cell,k= 50, bs="mrf", xt = list(nb = nb)) 
+s(cell,k=12, bs="mrf", xt = list(nb = nb),by=glost),<br>
~ s(DJFtas,bs='cr',k=10)+s(cell,k=50, bs="mrf", xt = list(nb = nb))+
s(cell,k=12, bs="mrf", xt = list(nb = nb),by=glost), <br>
~ s(DJFtas,bs='cr',k=10)+s(cell,k=50, bs="mrf", xt = list(nb = nb)))
<br>
extRemes time covariate : location.fun = ~glost, scale.fun = ~glost
##
