# Equivalence Exercises

1. \xy.xz is equivalent to b) \mn.mz
2. \xy.xxy is equivalent to c) \a.(\b.aab)
3. \xyz.zx is equivalent to b) \tos.st


# Chapter Exercises

## Combinators

1. \x.xxx is a combinator
2. \xy.zx is not a combinator
3. \xyz.xy(zx) is a combinator
4. \xyz.xy(zxy) is a combinator
5. \xy.xy(zxy) is not a combinator


## Normal form or diverge?

1. \x.xxx 
2. (\z.zz)(\y.yy)
   (\y.yy)(\y.yy) 
   this expression diverges
3. (\x.xxx)z
   zzz 
   this is the beta normal form

## Beta reduce

1. (\abc.cba)zz(\wv.w)
   (\bc.cbz)z(\wv.w)
   (\c.czz)(\wv.w)
   (\wv.w)zz
   (\v.z)z
   z

2. (\x.\y.xyy)(\a.a)b
   (\y.yy(\a.a))b
   (\a.a)bb
   bb

3. (\y.y)(\x.xx)(\z.zq)
   (\x.xx)(\z.zq)
   (\z.zq)(\z.zq)
   (\z.zq)q
   qq

4. (\z.z)(\z.zz)(\z.zy)
   (\z.zz)(\z.zy)
   (\z.zy)(\z.zy)
   (\z.zy)y
   yy

5. (\x.\y.xyy)(\y.y)y
   (\y.y)(\y.yy)y
   (\y.yy)y
   yy

6. (\a.aa)(\b.ba)c
   (\b.ba)(\b.ba)c
   (\b.ba)ac
   aac

7. (\xyz.xz(yz))(\x.z)(\x.a)
   (\z.(\x.z)z((\x.z)z))
   (\z.za)
