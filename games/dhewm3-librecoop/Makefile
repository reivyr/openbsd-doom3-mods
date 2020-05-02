# $OpenBSD: Makefile,v 1.13 2020/02/14 11:11:33 sthen Exp $

ONLY_FOR_ARCHS =	amd64 i386

V =	0.0.0.20200501
DISTNAME =	dhewm3-librecoop-${V}

GH_ACCOUNT =		Stradex
GH_PROJECT =		librecoop
GH_COMMIT =		5a900df87c9d09fc4358254df7fbfd4aef7a8221

COMMENT =		A Basic Coop for Doom 3

CATEGORIES =		games

# GPLv3+
PERMIT_PACKAGE =	Yes

WANTLIB += ${COMPILER_LIBCXX} m

MODULES =		devel/cmake

COMPILER =		base-clang ports-gcc

RUN_DEPENDS =		games/dhewm3

.include <bsd.port.mk>
