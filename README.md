# IOS-Brick-Prank
# 📱 iOS Brick Prank

A harmless iOS configuration-profile prank designed to make an iPhone look temporarily restricted.

> ⚠️ **IMPORTANT**
>
> This profile is reversible. Only install it on a device you own or have explicit permission to modify.
>
> **Do NOT use this to lock someone out of their device or prevent them from removing the profile.**

## 😈 What It Does

After installation, the profile may apply the included configuration restrictions.

The phone is **not actually bricked**. The device can be returned to normal by removing the profile.

## 🔄 Return the Phone to Normal

If you installed the profile and want to undo the prank:

1. Open **Settings**.
2. Go to **General**.
3. Select **VPN & Device Management**.
4. Find the installed configuration profile.
5. Tap the profile.
6. Select **Remove Profile**.
7. Enter the device passcode if iOS requests it.
8. Restart the iPhone if necessary.

Once the profile is removed, any restrictions controlled by that profile should stop applying.

## 🗑️ If You Don't See the Profile

Check:

**Settings → General → VPN & Device Management**

If there is no profile listed, the behavior may be coming from something other than the configuration profile.

## 🆘 Important Safety Notes

- Keep the original `.mobileconfig` file so you know exactly what was installed.
- Don't configure the profile to prevent its own removal.
- Don't use it to bypass Screen Time, parental controls, MDM, Activation Lock, or security protections.
- Don't install unknown certificates or profiles from untrusted sources.
- Only use the prank on devices where you have permission.

## 📄 Profile

`ios-brick-prank.mobileconfig`

The profile is intended as a temporary prank configuration, **not an actual device brick**.

## 🔓 Undo

**Settings → General → VPN & Device Management → Profile → Remove Profile**