# $NetBSD: Makefile,v 1.6 2021/06/01 14:35:44 taca Exp $

DISTNAME=	rex-powershell-0.1.90
CATEGORIES=	security

MAINTAINER=	minskim@NetBSD.org
HOMEPAGE=	https://github.com/rapid7/rex-powershell
COMMENT=	Ruby Exploitation library for generating Powershell scripts
LICENSE=	modified-bsd

USE_LANGUAGES=	# none

DEPENDS+=	${RUBY_PKGPREFIX}-rex-random_identifier-[0-9]*:../../security/ruby-rex-random_identifier
DEPENDS+=	${RUBY_PKGPREFIX}-rex-text-[0-9]*:../../security/ruby-rex-text
DEPENDS+=	${RUBY_PKGPREFIX}-rc4>=0:../../security/ruby-rc4

.include "../../lang/ruby/gem.mk"
.include "../../mk/bsd.pkg.mk"
