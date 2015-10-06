# Arch VGA Passthrough
This repo contains the notes, config files, scripts, etc. on how I got VGA passthrough working on Arch Linux in a Windows VM.

## What?
If you're unfamiliar, VGA passthrough is the process of giving a virtual machine full access tot the host machine's graphics card(s). Sounds easy? Not really... And for good reason since it violates the principles of sandboxing. Plus since it's not a common use-case scenario it's not heavily supported. BUT it can be very worth it in the long run!

## Why?
Well, in short: I got tired of booting into Windows... I recently switched to running Arch on my desktop bare-metal. I LOVE Linux, but I also love games and while Linux is catching up, most games still only support Windows. Normally my way around this is to run Windows on bare-metal and run Arch Linux in a VM. Works great... until I started getting into deeper development practices like running Vagrant machines. And lo and behold VirtualBox does not support nested virtualization. SO I did a swap! Arch Linux on bare-metal, Windows in a VM. This also works great for everything but games. So when I learned about VGA Passthrough I said, "Sign me up!".

## How?
Start by reading `How-To.md`.
