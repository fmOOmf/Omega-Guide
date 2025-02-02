---
title: "Vérifications finales"
---

{% include toc title="Sommaire" %}

### Vérification du bootloader STM32

Nous allons voir si le bootloader STM32 est effectivement déverrouillé :
1. Éteignez la calculatrice
2. Appuyez et maintenez la touche 6
3. Appuyez sur le bouton de réinitialisation à l'arrière de l'appareil

Si la LED devient rouge et que l'écran reste noir, tout va bien. Vous pouvez relâcher 6 et appuyer à nouveau sur reset pour revenir dans le firmware.

Si ce n'est pas le cas, rejoignez le [Discord Omega](https://discord.gg/X2TWhh9) et demandez de l'aide.
{: .notice--warning}


### GG!

Bravo, vous êtes maintenant l'heureux propriétaire d'un Numworks déverrouillée. Vous pouvez maintenant faire ce que vous voulez avec le matériel que vous avez acheté avec votre propre argent. Si vous le souhaitez, vous pouvez rejoindre le [Discord Omega](https://discord.gg/X2TWhh9) pour faire un coucou.

### Informations des mode sur Phi

Si vous avez installé le bootloader Phi, voici quelques informations dont vous pourriez avoir besoin.

- Vous pouvez accéder au bootloader STM32 DFU (appelé "hwloader") en maintenant 6 enfoncé tout en appuyant sur reset.
- Vous pouvez accéder au bootloader DFU de Phi (appelé "softloader") en maintenant 4 enfoncé tout en appuyant sur reset.

___

Si vous voulez utiliser Epsilon avec le nouveau bootloader, continuez vers [Installer Epsilon depuis le Softloader](install-epsilon-from-softloader)
{: .notice--info}
