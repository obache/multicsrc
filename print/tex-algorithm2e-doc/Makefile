# $NetBSD: Makefile,v 1.8 2020/01/18 23:33:32 rillig Exp $

DISTNAME=	algorithm2e.doc
PKGNAME=	tex-${DISTNAME:S/./-/}-5.2
TEXLIVE_REV=	44846

MAINTAINER=	pkgsrc-users@NetBSD.org
HOMEPAGE=	https://ctan.org/pkg/algorithm2e
COMMENT=	Documentation for tex-algorithm2e
LICENSE=	lppl-1.3c

CONFLICTS+=	tex-algorithm2e<4

TEXLIVE_UNVERSIONED=	yes
.include "../../print/texlive/package.mk"
.include "../../mk/bsd.pkg.mk"
