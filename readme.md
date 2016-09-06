# docker-zsh-completion

My personal fork of felixr's docker completion plugin. 

A [zsh](http://zsh.org) completion for
[docker](http://docker.io). This completion has been merged into
docker official repository and receives various updates. This
repository is kept up-to-date but, except for one small detail, there
should not be no difference.

# Contributors

* [ninrod](http://github.com/ninrod)
* [felixr](http://github.com/felixr)
* [vincentbernat](http://github.com/vincentbernat)
* [sdurrheimer](https://github.com/sdurrheimer)

And many others as most commits now come directly from Docker. Patches
are applied this way:

    $ cd docker/contrib/completion/zsh
    $ git format-patch --stdout -1 d736a9d2c3758fcc4eac0b62e9c7b128388021c1 -- ./_docker | \
        (cd ~/.zsh/third-party/docker-zsh-completion ; git am -p4 )

# License (BSD License)

    Copyright (c) 2013, Felix Riedel
    All rights reserved.
    
    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions are met:
        * Redistributions of source code must retain the above copyright
          notice, this list of conditions and the following disclaimer.
        * Redistributions in binary form must reproduce the above copyright
          notice, this list of conditions and the following disclaimer in the
          documentation and/or other materials provided with the distribution.
        * Neither the name of the <organization> nor the
          names of its contributors may be used to endorse or promote products
          derived from this software without specific prior written permission.
    
    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
    ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
    WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
    DISCLAIMED. IN NO EVENT SHALL <COPYRIGHT HOLDER> BE LIABLE FOR ANY
    DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
    (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
    LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
    ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
    (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
    SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

