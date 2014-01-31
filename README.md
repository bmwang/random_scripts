#random_scripts

Random scripts that I've used at least once.

##imgdiff
Diffs two images. Requires PIL (and appropriate image libraries).
`pip install pillow` to get PIL.

Primarily written to see small differences in two rendered images.

Example usage:
`imgdiff input_img1.jpg input_img2.jpg output_diff.jpg`

##sshsockstunnel
Opens a SSH connection and sets the appropriate system preferences in OSX.

Primary written to SOCKS proxy through my machine at work.

Requires sudo access to touch preferences.

Example usage: 
`sshsockstunnel --host brandonwang@brandonwang.net --adaptors Wi-Fi`

