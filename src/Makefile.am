
lib_LTLIBRARIES = libftgl.la

libftgl_la_SOURCES = \
    FTBuffer.cpp \
    FTCharmap.cpp \
    FTCharmap.h \
    FTCharToGlyphIndexMap.h \
    FTContour.cpp \
    FTContour.h \
    FTFace.cpp \
    FTFace.h \
    FTGlyphContainer.cpp \
    FTGlyphContainer.h \
    FTInternals.h \
    FTLibrary.cpp \
    FTLibrary.h \
    FTList.h \
    FTPoint.cpp \
    FTSize.cpp \
    FTSize.h \
    FTVector.h \
    FTVectoriser.cpp \
    FTVectoriser.h \
    FTUnicode.h \
    $(ftglyph_sources) \
    $(ftfont_sources) \
    $(ftlayout_sources) \
    $(ftgl_headers) \
    $(NULL)
libftgl_la_CPPFLAGS = -IFTGlyph -IFTFont -IFTLayout
libftgl_la_CXXFLAGS = $(FT2_CFLAGS) $(GL_CFLAGS)
libftgl_la_LDFLAGS = \
        -no-undefined -version-number $(LT_VERSION) -framework OpenGLES
libftgl_la_LIBADD = \
	$(FT2_LIBS) 

ftgldir = $(includedir)/FTGL
ftgl_HEADERS = $(ftgl_headers)

ftgl_headers = \
    FTGL/ftgles.h \
    FTGL/ftglesGlue.h \
    FTGL/ftglesGlue.cpp \
    FTGL/FTBBox.h \
    FTGL/FTBuffer.h \
    FTGL/FTPoint.h \
    FTGL/FTGlyph.h \
    FTGL/FTBitmapGlyph.h \
    FTGL/FTBufferGlyph.h \
    FTGL/FTOutlineGlyph.h \
    FTGL/FTTextureGlyph.h \
    FTGL/FTFont.h \
    FTGL/FTGLBitmapFont.h \
    FTGL/FTBufferFont.h \
    FTGL/FTGLExtrdFont.h \
    FTGL/FTGLOutlineFont.h \
    FTGL/FTGLTextureFont.h \
    FTGL/FTLayout.h \
    FTGL/FTSimpleLayout.h \
    ${NULL}

ftglyph_sources = \
    FTGlyph/FTGlyph.cpp \
    FTGlyph/FTGlyphImpl.h \
    FTGlyph/FTGlyphGlue.cpp \
    FTGlyph/FTBitmapGlyph.cpp \
    FTGlyph/FTBitmapGlyphImpl.h \
    FTGlyph/FTBufferGlyph.cpp \
    FTGlyph/FTBufferGlyphImpl.h \
    FTGlyph/FTOutlineGlyph.cpp \
    FTGlyph/FTOutlineGlyphImpl.h \
    FTGlyph/FTTextureGlyph.cpp \
    FTGlyph/FTTextureGlyphImpl.h \
    $(NULL)

ftfont_sources = \
    FTFont/FTFont.cpp \
    FTFont/FTFontImpl.h \
    FTFont/FTFontGlue.cpp \
    FTFont/FTBitmapFont.cpp \
    FTFont/FTBitmapFontImpl.h \
    FTFont/FTBufferFont.cpp \
    FTFont/FTBufferFontImpl.h \
    FTFont/FTOutlineFont.cpp \
    FTFont/FTOutlineFontImpl.h \
    FTFont/FTTextureFont.cpp \
    FTFont/FTTextureFontImpl.h \
    $(NULL)

ftlayout_sources = \
    FTLayout/FTLayout.cpp \
    FTLayout/FTLayoutImpl.h \
    FTLayout/FTLayoutGlue.cpp \
    FTLayout/FTSimpleLayout.cpp \
    FTLayout/FTSimpleLayoutImpl.h \
    $(NULL)

NULL =
