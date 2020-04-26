# $OpenBSD: Makefile,v 1.13 2020/02/14 11:11:33 sthen Exp $

ONLY_FOR_ARCHS =	amd64 i386

V =	0.0.0.20191228
DISTNAME =	dhewm3-librecoop-${V}

GH_ACCOUNT =		Stradex
GH_PROJECT =		librecoop
GH_COMMIT =		97ba7384b63c2f6c2a50196177f9d0985b02d609

COMMENT =		A Basic Coop for Doom 3

CATEGORIES =		games

# GPLv3+
PERMIT_PACKAGE =	Yes

WANTLIB += ${COMPILER_LIBCXX} m

MODULES =		devel/cmake

COMPILER =		base-clang ports-gcc

RUN_DEPENDS =		games/dhewm3

.include <bsd.port.mk>
