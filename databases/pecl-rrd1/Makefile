# $FreeBSD$

PORTNAME=	rrd
DISTVERSION=	1.1.3
CATEGORIES=	databases pear
PKGNAMESUFFIX=	1

MAINTAINER=	daniel@blodan.se
COMMENT=	PHP bindings to rrd tool system

LICENSE=	PHP301

IGNORE_WITH_PHP=70 71
LIB_DEPENDS=	librrd.so:databases/rrdtool
USES=		php:pecl localbase pkgconfig

.include <bsd.port.mk>
