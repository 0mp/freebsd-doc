#
# $FreeBSD$
#
# ����������� ��� FreeBSD FAQ
#
# %SOURCE%	en_US.ISO8859-1/books/faq/Makefile
# %SRCID%	1.12
#

MAINTAINER=doc@FreeBSD.org

DOC?= book

FORMATS?= html-split html

INSTALL_COMPRESSED?= gz
INSTALL_ONLY_COMPRESSED?=

WITH_BIBLIOXREF_TITLE?=YES

#
# � ����� SRCS �������� ��� �� XML ������ ��� ��������� ���� ��� ��������.
# ������� �� ����������� ��� ���� �� ������ ��������� rebuild.
#

# XML content
SRCS=  book.xml

URL_RELPREFIX?=	../../../..
DOC_PREFIX?=	${.CURDIR}/../../..

.include "${DOC_PREFIX}/share/mk/doc.project.mk"
