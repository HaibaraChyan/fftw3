AM_CPPFLAGS = -I $(top_srcdir)
noinst_LTLIBRARIES = libsimd_support.la 

noinst_PROGRAMS =

libsimd_support_la_SOURCES = taint.c simd-common.h \
x86-cpuid.h amd64-cpuid.h \
simd-sse2.h sse2.c \
avx.c simd-avx.h \
avx-128-fma.c simd-avx-128-fma.h \
avx2.c simd-avx2.h simd-avx2-128.h \
avx512.c simd-avx512.h \
kcvi.c simd-kcvi.h \
altivec.c simd-altivec.h vsx.c simd-vsx.h \
neon.c simd-neon.h \
lsx.c simd-lsx.h \
lasx.c simd-lasx.h \
simd-generic128.h simd-generic256.h \
sve.c simd-maskedsve.h simd-maskedsve128.h simd-maskedsve256.h simd-maskedsve512.h simd-maskedsve1024.h simd-maskedsve2048.h
