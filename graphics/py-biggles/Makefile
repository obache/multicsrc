# $NetBSD: Makefile,v 1.30 2020/10/12 21:52:00 bacon Exp $

DISTNAME=	python2-biggles-1.6.6
PKGNAME=	${PYPKGPREFIX}${DISTNAME:S/python2//}
PKGREVISION=	1
CATEGORIES=	graphics python
MASTER_SITES=	${MASTER_SITE_SOURCEFORGE:=biggles/}

MAINTAINER=	Kai.Puolamaki@iki.fi
HOMEPAGE=	http://biggles.sourceforge.net/
COMMENT=	Python module for creating 2D scientific plots

PYTHON_VERSIONS_ACCEPTED=	27 # not ported yet as of 1.6.6

.include "../../lang/python/distutils.mk"
.include "../../math/py-numpy/buildlink3.mk"
.include "../../graphics/plotutils/buildlink3.mk"
.include "../../mk/bsd.pkg.mk"
