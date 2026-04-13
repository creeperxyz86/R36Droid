<h1>R36Droid</h1>
Welcome to the official repository for R36Droid, a specialized Android build optimized for R36S and R36H clone devices. Our mission is to provide a stable, high-performance experience on the RK3326 platform.

👥 The Team
Lead Developer: @creeperxyz86, @itskenny0 (Kernel, Hardware Abstraction, & Base System)

System Architect: @phamtrungdang69-a11y (Optimization, Memory Management, & Documentation)

⚠️ CRITICAL: READ BEFORE OPENING AN ISSUE
To keep development efficient and the repository clean, we strictly enforce the following rules. Failure to follow these will result in your issue being CLOSED or LOCKED immediately.

🚫 NO "PANEL X" SPAMMING
We are well aware of the display issues on various clone panels. Do NOT open a new issue just to say "My screen is black" or "Panel X doesn't work."

Check existing issues first.

If you have a new panel variant, provide Technical Logs (Logcat) and DTS/DTB files.

Do NOT send "Assignees" requests to the developers. We manage our own tasks.

💡 TECHNICAL FEEDBACK & SUGGESTIONS
If you have suggestions for system optimization, UI refinements, or virtual controller mapping:

Open an issue with a clear technical description.

Tag @phamtrungdang69-a11y in your comment for architectural review.

Provide evidence/metrics (RAM usage, Boot time, etc.) if possible.

🔌 POWER & SAFETY (ISSUE #85 from Andr36oid project from @sonic011gamer)
DO NOT use high-speed PD chargers or USB-C to USB-C cables. This causes "false voltage" and BMS glitches, leading to boot loops and data corruption.

Use ONLY USB-A to USB-C original cables.

Use 5V-1A/1.5A power bricks.

🚀 Optimization Roadmap
Managed by the System Architect, we are currently focusing on:

Virtual Mouse Mode: Joystick-to-mouse mapping for touchless navigation.

Memory Mastery: Tuning LMK (Low Memory Killer) and OOM parameters for 1GB/2GB environments.

Lightweight Environment: Replacing heavy frontends with ultra-lightweight alternatives (Hyperdroid, Via Browser).

🛠️ How to Contribute
We value quality over quantity. If you want to contribute:

Decompile your DTB: Don't just send a .zip or .bin from a random site.

Describe your hardware: Motherboard version (e.g., V1.2) is mandatory.

No MediaFire/Sketchy links: Use GitHub Gist, Pastebin, or attach files directly to the issue.
