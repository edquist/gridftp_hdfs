
lib_LTLIBRARIES = libglobus_gridftp_server_hdfs.la

JNIHDIR=@JNIHDIR@
INCLUDES= -I$(JNIHDIR) -I$(JNIHDIR)/linux @INCLUDE@

#libglobus_gridftp_server_hdfs_la_SOURCES = globus_gridftp_server_hdfs.c
libglobus_gridftp_server_hdfs_la_LDFLAGS = -lhdfs -lcrypto -lz
libglobus_gridftp_server_hdfs_la_SOURCES = \
    gridftp_hdfs.h \
    gridftp_hdfs_error.h \
    gridftp_hdfs.c \
    gridftp_hdfs_recv.c \
    gridftp_hdfs_send.c \
    gridftp_hdfs_stat.c \
    gridftp_hdfs_buffers.c \
    gridftp_hdfs_cksm.c

