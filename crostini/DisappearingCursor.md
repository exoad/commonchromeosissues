# Description
If your cursor for some reason in Linux (Beta) apps somehow disappeared paste the following command into your Linux terminal:

```
mkdir -p ~/.config/systemd/user/sommelier-x@.service.d
cat > ~/.config/systemd/user/sommelier-x@.service.d/sommelier-x-override.conf <<EOF
[Service]
Environment="VIRGL_DEBUG=xfer"
EOF
```

**Source(s):**
[Reddit Post #1](https://www.reddit.com/r/chromeos/comments/mx567r/if_your_cursor_does_not_appear_in_certainall/)
