#Series7GentooKernelConfig#

A working Gentoo kernel configuration for my Samsung Series 7 Chrome notebook.

###Installation###
clone repo

<pre><code>
echo ">sys-kernel/gentoo-sources-3.2.48">>/etc/portage/package.mask
emerge -av genkernel
emerge -av gentoo-sources
ln -s /usr/src/linux-3.2.48-gentoo /usr/src/linux
genkernel --config=theconfig all
</code></pre>
