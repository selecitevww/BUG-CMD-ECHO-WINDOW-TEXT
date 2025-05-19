
#RUN IN BAT FILE^:

> Y:
> 
> cd ..
> 
> cd ..
> 
> cd ..
> 
> cd ..
> 
> FOR /r  %%G in ("*") Do (@echo hue & ECHO %%G=@cd .. & cd.. & cd .. )
