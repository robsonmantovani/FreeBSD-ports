# Created by: Wen Heping <wenheping@gmail.com>
# $FreeBSD$

PORTNAME=	Math-MPC
PORTVERSION=	1.07
CATEGORIES=	math perl5
MASTER_SITES=	CPAN
PKGNAMEPREFIX=	p5-

MAINTAINER=	perl@FreeBSD.org
COMMENT=	Perl interface to MPC Library

LICENSE=	ART10 GPLv1+
LICENSE_COMB=	dual

BUILD_DEPENDS=	p5-Math-MPFR>=3.23:math/p5-Math-MPFR
LIB_DEPENDS=	libgmp.so:math/gmp \
		libmpc.so:math/mpc \
		libmpfr.so:math/mpfr
RUN_DEPENDS:=	${BUILD_DEPENDS}

USE_PERL5=	configure
USES=		localbase perl5

post-install:
	${STRIP_CMD} ${STAGEDIR}${SITE_ARCH}/auto/Math/MPC/MPC.so

.include <bsd.port.mk>
