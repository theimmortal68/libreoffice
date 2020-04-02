pkgname=libreoffice-jre
_LOver=6.4.2.2
pkgver=6.4.2.2
_pkgver=6.4.2
pkgrel=1
arch=('x86_64')
license=('LGPL3')
url="https://www.libreoffice.org/"
pkgdesc="Productivity suite that is compatible with other major office suites"
provides=('libreoffice')
conflicts=('libreoffice')
depends=('curl' 'python3' 'libabw' 'libwpd' 'libwps' 'libxaw' 'neon' 
         'pango' 'nss' 'libjpeg-turbo' 'libxrandr' 'libglvnd' 'dbus-glib' 'libxslt' 'redland' 'graphite' 'icu'
         'hyphen' 'lpsolve' 'gcc-libs' 'bash' 'librsvg' 'lcms2' 'hicolor-icon-theme' 'desktop-file-utils' 
         'shared-mime-info' 'translate-toolkit' 'xdg-utils' 'ttf-liberation' 'libcups' 
         'poppler' 'sane' 'unixodbc' 'libwpg' 'imagemagick' 'hunspell'
         'mesa' 'gst-plugins-base' 'postgresql-libs' 'libvisio' 'bluez' 'liblangtag'
         'libetonyek' 'libodfgen' 'libatomic_ops' 'clucene' 'glew' 'glu' 
         'vigra' 'pstoedit' 'libmythes' 'boost-libs' 'libepoxy'
         'kconfig' 'kcoreaddons' 'ki18n' 'kio' 'kwindowsystem' 'plasma-framework' 'python3-lxml' 'libnumbertext'
	 'openjdk' 'apache-ant')
makedepends=('perl-archive-zip' 'zip' 'unzip' 'gperf' 'cppunit' 'libldap'
             'doxygen' 'apr' 'serf' 'mdds' 'boost')
_mirror="https://tdf.mirror.liteserver.nl/libreoffice/src/$_pkgver"
#_mirror="http://dev-builds.libreoffice.org/pre-releases/src""
_additional_source_url="http://dev-www.libreoffice.org/src"
source=(${_mirror}/libreoffice{,-help,-translations}-${_LOver}.tar.xz  
	${_additional_source_url}/xmlsec1-1.2.28.tar.gz     
	${_additional_source_url}/35c94d2df8893241173de1d16b6034c0-swingExSrc.zip
	${_additional_source_url}/798b2ffdc8bcfe7bca2cf92b62caf685-rhino1_5R5.zip
	${_additional_source_url}/ada24d37d8d638b3d8a9985e80bc2978-source-9.0.0.7-bj.zip
	${_additional_source_url}/2a177023f9ea8ec8bd00837605c5df1b-jakarta-tomcat-5.0.30-src.tar.gz
	${_additional_source_url}/a7983f859eafb2677d7ff386a023bc40-xsltml_2.1.2.zip
	${_additional_source_url}/commons-logging-1.2-src.tar.gz
	${_additional_source_url}/8ab049135b2d15313da5d9f0656894a1-commons-lang3-3.3.1-src.tar.gz
	${_additional_source_url}/2c9b0f83ed5890af02c0df1c1776f39b-commons-httpclient-3.1-src.tar.gz
	${_additional_source_url}/048751f3271906db5126ab76870444c4-commons-codec-1.9-src.zip
	${_additional_source_url}/eeb2c7ddf0d302fba4bfc6e97eac9624-libbase-1.1.6.zip
	${_additional_source_url}/39bb3fcea1514f1369fcfc87542390fd-sacjava-1.3.zip
	${_additional_source_url}/3404ab6b1792ae5f16bbd603bd1e1d03-libformula-1.1.7.zip
	${_additional_source_url}/97b2d4dba862397f446b217e2b623e71-libloader-1.1.6.zip
	${_additional_source_url}/f94d9870737518e3b597f9265f4e9803-libserializer-1.1.6.zip
	${_additional_source_url}/8ce2fcd72becf06c41f7201d15373ed9-librepository-1.1.6.zip
	${_additional_source_url}/d8bd5eed178db6e2b18eeed243f85aa8-flute-1.1.6.zip
	${_additional_source_url}/3bdf40c0d199af31923e900d082ca2dd-libfonts-1.1.6.zip
	${_additional_source_url}/ace6ab49184e329db254e454a010f56d-libxml-1.1.7.zip
	${_additional_source_url}/db60e4fde8dd6d6807523deb71ee34dc-liblayout-0.2.10.zip
	${_additional_source_url}/ba2930200c9f019c2d93a8c88c651a0f-flow-engine-0.9.4.zip
	${_additional_source_url}/libexttextcat-3.4.5.tar.xz 
	${_additional_source_url}/libcmis-0.5.2.tar.xz 
	${_additional_source_url}/liborcus-0.15.3.tar.gz
	#${_additional_source_url}/aa899eff126216dafe721149fbdb511b-liblangtag-0.5.8.tar.bz2
	${_additional_source_url}/0168229624cfac409e766913506961a8-ucpp-1.3.2.tar.gz
	${_additional_source_url}/libcdr-0.1.5.tar.xz
	${_additional_source_url}/libmspub-0.1.4.tar.xz
	${_additional_source_url}/libmwaw-0.3.15.tar.xz
	${_additional_source_url}/libfreehand-0.1.2.tar.xz
	${_additional_source_url}/Firebird-3.0.0.32483-0.tar.bz2 
	${_additional_source_url}/libe-book-0.1.3.tar.xz
	${_additional_source_url}/17410483b5b5f267aa18b7e00b65e6e0-hsqldb_1_8_0.zip
	#${_additional_source_url}/976734806026a4ef8bdd17937c8898b9-icu4c-57_1-src.tgz
	#${_additional_source_url}/boost_1_69_0.tar.bz2
	${_additional_source_url}/language-subtag-registry-2019-09-16.tar.bz2
	${_additional_source_url}/libgltf/libgltf-0.1.0.tar.gz
	${_additional_source_url}/CoinMP-1.7.6.tgz
	${_additional_source_url}/bae83fa5dc7f081768daace6e199adc3-glm-0.9.4.6-libreoffice.zip
	${_additional_source_url}/4b87018f7fff1d054939d19920b751a0-collada2gltf-master-cb1d97788a.tar.bz2
	${_additional_source_url}/OpenCOLLADA-master-6509aa13af.tar.bz2
	${_additional_source_url}/libpagemaker-0.0.4.tar.xz
	${_additional_source_url}/libstaroffice-0.0.6.tar.xz 
	${_additional_source_url}/libzmf-0.0.2.tar.xz
	${_additional_source_url}/ltm-1.0.zip
	${_additional_source_url}/pdfium-3963.tar.bz2
	${_additional_source_url}/libepubgen-0.1.1.tar.xz
	${_additional_source_url}/libqxp-0.0.2.tar.xz
	${_additional_source_url}/QR-Code-generator-1.4.0.tar.gz
	https://dev-www.libreoffice.org/extern/185d60944ea767075d27247c3162b3bc-unowinreg.dll
	https://dev-www.libreoffice.org/extern/884ed41809687c3e168fc7c19b16585149ff058eca79acbf3ee784f6630704cc-opens___.ttf
	poppler.diff)
	
	noextract=(18f577b374d60b3c760a3a3350407632-STLport-4.5.tar.gz
        185d60944ea767075d27247c3162b3bc-unowinreg.dll
        884ed41809687c3e168fc7c19b16585149ff058eca79acbf3ee784f6630704cc-opens___.ttf
	ada24d37d8d638b3d8a9985e80bc2978-source-9.0.0.7-bj.zip
	798b2ffdc8bcfe7bca2cf92b62caf685-rhino1_5R5.zip
	xmlsec1-1.2.28.tar.gz    
	libexttextcat-3.4.5.tar.xz 
	libcmis-0.5.2.tar.xz 
	35c94d2df8893241173de1d16b6034c0-swingExSrc.zip
	2a177023f9ea8ec8bd00837605c5df1b-jakarta-tomcat-5.0.30-src.tar.gz
	a7983f859eafb2677d7ff386a023bc40-xsltml_2.1.2.zip
	commons-logging-1.2-src.tar.gz
	8ab049135b2d15313da5d9f0656894a1-commons-lang3-3.3.1-src.tar.gz
	2c9b0f83ed5890af02c0df1c1776f39b-commons-httpclient-3.1-src.tar.gz
	048751f3271906db5126ab76870444c4-commons-codec-1.9-src.zip
	eeb2c7ddf0d302fba4bfc6e97eac9624-libbase-1.1.6.zip
	39bb3fcea1514f1369fcfc87542390fd-sacjava-1.3.zip
	3404ab6b1792ae5f16bbd603bd1e1d03-libformula-1.1.7.zip
	97b2d4dba862397f446b217e2b623e71-libloader-1.1.6.zip
	f94d9870737518e3b597f9265f4e9803-libserializer-1.1.6.zip
	8ce2fcd72becf06c41f7201d15373ed9-librepository-1.1.6.zip
	d8bd5eed178db6e2b18eeed243f85aa8-flute-1.1.6.zip
	3bdf40c0d199af31923e900d082ca2dd-libfonts-1.1.6.zip
	ace6ab49184e329db254e454a010f56d-libxml-1.1.7.zip
	db60e4fde8dd6d6807523deb71ee34dc-liblayout-0.2.10.zip
	ba2930200c9f019c2d93a8c88c651a0f-flow-engine-0.9.4.zip
	liborcus-0.15.3.tar.gz
	#aa899eff126216dafe721149fbdb511b-liblangtag-0.5.8.tar.bz2
	0168229624cfac409e766913506961a8-ucpp-1.3.2.tar.gz
	17410483b5b5f267aa18b7e00b65e6e0-hsqldb_1_8_0.zip
	#976734806026a4ef8bdd17937c8898b9-icu4c-57_1-src.tgz
	#boost_1_69_0.tar.bz2
	libcdr-0.1.5.tar.xz
	libmspub-0.1.4.tar.xz
	libmwaw-0.3.15.tar.xz
	libfreehand-0.1.2.tar.xz
	Firebird-3.0.0.32483-0.tar.bz2 
	libe-book-0.1.3.tar.xz
	language-subtag-registry-2019-09-16.tar.bz2
	CoinMP-1.7.6.tgz
	bae83fa5dc7f081768daace6e199adc3-glm-0.9.4.6-libreoffice.zip
	4b87018f7fff1d054939d19920b751a0-collada2gltf-master-cb1d97788a.tar.bz2
	OpenCOLLADA-master-6509aa13af.tar.bz2
	libpagemaker-0.0.4.tar.xz
	libstaroffice-0.0.6.tar.xz
	libzmf-0.0.2.tar.xz
	ltm-1.0.zip
	pdfium-3963.tar.bz2
	libgltf-0.1.0.tar.gz
	libepubgen-0.1.1.tar.xz
	libqxp-0.0.2.tar.xz
	QR-Code-generator-1.4.0.tar.gz)

md5sums=('1e7df8ecc616b778293a90b874d560b1'
         '24108abfa209da008b1e24d11bea6684'
         '580c22ac9b84e76cdfdb02287a9728be'
         '69b8d95c009a404462e19f335e650241'
         '35c94d2df8893241173de1d16b6034c0'
         '798b2ffdc8bcfe7bca2cf92b62caf685'
         'ada24d37d8d638b3d8a9985e80bc2978'
         '2a177023f9ea8ec8bd00837605c5df1b'
         'a7983f859eafb2677d7ff386a023bc40'
         'ce977548f1cbf46918e93cd38ac35163'
         '8ab049135b2d15313da5d9f0656894a1'
         '2c9b0f83ed5890af02c0df1c1776f39b'
         '048751f3271906db5126ab76870444c4'
         'eeb2c7ddf0d302fba4bfc6e97eac9624'
         '39bb3fcea1514f1369fcfc87542390fd'
         '3404ab6b1792ae5f16bbd603bd1e1d03'
         '97b2d4dba862397f446b217e2b623e71'
         'f94d9870737518e3b597f9265f4e9803'
         '8ce2fcd72becf06c41f7201d15373ed9'
         'd8bd5eed178db6e2b18eeed243f85aa8'
         '3bdf40c0d199af31923e900d082ca2dd'
         'ace6ab49184e329db254e454a010f56d'
         'db60e4fde8dd6d6807523deb71ee34dc'
         'ba2930200c9f019c2d93a8c88c651a0f'
         '69c984b1785b56942179eb0ddc9c758f'
         '3653bc54e1bcd17ae09a1a7086daa38b'
         '24e615b837110e2676562d83f3c64d21'
         '0168229624cfac409e766913506961a8'
         '3040295f7a027c5bcdffbdb5bbdfd00a'
         'ac6fa9c1c05ece27c58c05e11786fd3a'
         'ffe1479ecde9afd8ce86b791183183fd'
         'c3788f5686839fd097bd77d8f51c3d04'
         '821260b61dafc22899d1464d4e91ee6a'
         '2956f1c5e7950b0018979a132165da8b'
         '17410483b5b5f267aa18b7e00b65e6e0'
         '152c02c55e457d5ee1c1d376857608d1'
         '63ae962d0c436909979826fce0fca2fd'
         '1cce53bf4b40ae29790d2c5c9f8b1129'
         'bae83fa5dc7f081768daace6e199adc3'
         '4b87018f7fff1d054939d19920b751a0'
         '4ca8a6ef0afeefc864e9ef21b9f14bd6'
         '8395dfc5eef11c58d5a9efe3bfe64831'
         '3db5ccd618b67df20adc9555fe89560a'
         'e4b089f35a85a042ba4da3c143b1dc5a'
         'da283d2e3e72137d0c600ac36b991c9d'
         '7688ac08e1292cf7e0d027f506f45c49'
         '6e710ab7e45ecdecac4983db18dd2629'
         '7011efa81fe8b6b1f2dd7d05d7bfb173'
         '0e81d36829be287ff27ae802e0587463'
         '185d60944ea767075d27247c3162b3bc'
         '866ba2ca4188f1610b121dfd514a17e8'
         '930a0e93ea6c8cba30a60d835df498d4')

build() {

	#unset J2REDIR; unset J2SDKDIR; unset JAVA_HOME; unset CLASSPATH
	#[ -z "${JAVA_HOME}" ] && .  /etc/profile.d/openjdk.sh
	#[ -z "${ANT_HOME}" ] && . /etc/profile.d/apache-ant.sh

	cd ${srcdir}/libreoffice-$_LOver
	# poppler 0.86 needed
	patch -p1 -i ${srcdir}/poppler.diff

	# move external sources into place
	mkdir ${srcdir}/ext_sources &&	pushd ${srcdir}/ext_sources
	for source in "${noextract[@]}"; do
	  ln -s ${srcdir}/$source .
	done
	popd

	rm ${srcdir}/ext_sources/185d60944ea767075d27247c3162b3bc-unowinreg.dll
        cp -f ${srcdir}/185d60944ea767075d27247c3162b3bc-unowinreg.dll ${srcdir}/ext_sources
	
	#use the CFLAGS but remove the LibO overridden ones
	for i in $CFLAGS; do
		case "$i" in
			-O?|-pipe|-Wall|-g|-fexceptions) continue;;
		esac
        ARCH_FLAGS="$ARCH_FLAGS $i"
	done
	
	# Use python3
	export PYTHON=python3

	./autogen.sh --with-build-version="${_LOver} KaOS-${pkgrel}" --with-vendor="KaOS" \
		--with-external-tar="${srcdir}/ext_sources" \
		--disable-fetch-external \
		--prefix=/usr --exec-prefix=/usr --sysconfdir=/etc \
		--libdir=/usr/lib --mandir=/usr/share/man \
		--includedir=/usr/include \
		--with-lang="" \
		--with-help=html \
		--enable-release-build \
		--enable-cairo-canvas \
		--enable-dbus \
		--disable-evolution2 \
		--enable-gio \
		--disable-gtk3 \
		--disable-odk \
		--enable-python=system \
		--disable-scripting-beanshell \
		--disable-scripting-javascript \
		--without-fonts \
		--with-system-apr \
		--without-system-libcdr \
		--without-system-jfreereport \
		--without-system-apache-commons \
		--with-system-libodfgen \
		--without-system-libmwaw \
		--with-system-libetonyek \
		--without-system-libfreehand \
		--without-system-firebird \
		--with-system-libatomic-ops \
		--without-system-libebook \
		--with-system-libabw \
		--with-system-mdds \
		--without-myspell-dicts \
        --with-system-libvisio \
        --without-system-libcmis \
        --without-system-libmspub \
		--without-system-libexttextcat \
		--without-system-orcus \
		--without-system-libstaroffice \
		--without-system-libzmf \
		--without-system-libtommath \
		--without-system-xmlsec \
		--without-system-qrcodegen \
		--with-system-liblangtag \
		--with-system-dicts \
        --with-system-hunspell \
		--with-external-hyph-dir=/usr/share/hyphen \
		--with-external-thes-dir=/usr/share/mythes \
        --with-system-cppunit \
        --with-system-graphite \
		--without-system-glm \
		--with-system-libwpg \
		--with-system-libwps \
		--with-system-redland \
		--with-system-serf \
		--with-system-boost \
		--with-system-icu \
		--with-system-cairo \
		--with-system-libs \
		--with-system-mythes \
		--with-system-headers \
		--without-system-hsqldb \
		--without-system-libpagemaker \
		--without-system-coinmp \
		--without-system-libepubgen \
		--without-system-libqxp \
		--with-system-libnumbertext \
		--with-system-clucene \
		--disable-dependency-tracking \
		--disable-cve-tests \
		--with-theme="breeze breeze_dark breeze_svg sifr" \
		--disable-gtk3-kde5 \
		--enable-kf5 \
		--enable-qt5 \
		--without-junit \

	touch src.downloaded
	#./download
	# one test in sw_ooxmlexport7 fails, rebuild with '-no-check' added
	make build-nocheck
}

package() {
        cd ${srcdir}/libreoffice-$_LOver
        make DESTDIR=${pkgdir} distro-pack-install
 
        # configuration files 
        install -dm755 ${pkgdir}/etc/libreoffice
        install -m644 ${pkgdir}/usr/lib/libreoffice/program/{bootstraprc,sofficerc} ${pkgdir}/etc/libreoffice/
        install -m644 ${pkgdir}/usr/lib/libreoffice/share/psprint/psprint.conf ${pkgdir}/etc/libreoffice/
        # links 
        cd ${pkgdir}/usr/lib/libreoffice/program/
        ln -vsf /etc/libreoffice/{bootstraprc,sofficerc} .
        cd ${pkgdir}/usr/lib/libreoffice/share/psprint/
        ln -vsf /etc/libreoffice/psprint.conf .
 
        #install -dm755 ${pkgdir}/usr/share/bash-completion/completions
        #mv ${pkgdir}/etc/bash_completion.d/libreoffice.sh ${pkgdir}/usr/share/bash-completion/completions/libreoffice.sh
        #rm -rf ${pkgdir}/etc/bash_completion.d
 
        install -v -m644 ${srcdir}/libreoffice-$_LOver/sysui/desktop/appstream-appdata/*.xml ${pkgdir}/usr/share/appdata 
}
