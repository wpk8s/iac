FROM wordpress:5.6.1

RUN set -eux; \
	{ \
		echo 'upload_max_filesize=1G'; \
		echo 'post_max_size=1G'; \
	} > /usr/local/etc/php/conf.d/upload.ini
