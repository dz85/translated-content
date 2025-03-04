---
title: windows.WindowState
slug: Mozilla/Add-ons/WebExtensions/API/windows/WindowState
tags:
  - API
  - Add-ons
  - Extensions
  - Non-standard
  - Reference
  - Type
  - WebExtensions
  - WindowState
  - Windows
translation_of: Mozilla/Add-ons/WebExtensions/API/windows/WindowState
---
{{AddonSidebar()}}

L'état de cette fenêtre du navigateur.

## Type

Les valeurs de ce type sont des chaînes. Les valeurs possibles sont:

- `"normal"`
  - : La fenêtre est à la taille par défaut ou à la taille sélectionnée par l'utilisateur.
- `"minimized"`
  - : La fenêtre n'est visible que sous la forme d'une icône dans la barre des tâches ou .
- `"maximized"`
  - : La fenêtre remplit l'écran sur lequel elle est affichée sans inclure les zones d'écran réservées par le système d'exploitation.
- `"fullscreen"`
  - : La fenêtre s'exécute en plein écran ou le contenu d'un onglet utilise l'[API Fullscreen](/fr/docs/Web/API/Fullscreen_API)
- `"docked"`
  - : Une fenêtre ancrée occupe une position fixe par rapport aux autres fenêtres appartenant à la même application.

Compatibilité macOS : A partir de macOS 10.10, le comportement de maximisation par défaut pour les fenêtres a été modifié pour exécuter les applications en plein écran au lieu des fenêtres "zoomées". `fullscreen` fait référence à la fois au navigateur fonctionnant en plein écran et lorsque le contenu dans un onglet utilise l'API Fullscreen.

## Compatibilité du navigateur

{{Compat("webextensions.api.windows.WindowState")}}

{{WebExtExamples}}

> **Note :**
>
> Cette API est basée sur l'API de Chromnium [`chrome.windows`](https://developer.chrome.com/extensions/windows). Cette documentation provient de [`windows.json`](https://chromium.googlesource.com/chromium/src/+/master/chrome/common/extensions/api/windows.json) dans le code de Chromium.
>
> Les données de compatibilité Microsoft Edge sont fournies par Microsoft Corporation et sont incluses ici sous la licence Creative Commons Attribution 3.0 United States.

<div class="hidden"><pre>// Copyright 2015 The Chromium Authors. All rights reserved.
//
// Redistribution and use in source and binary forms, with or without
// modification, are permitted provided that the following conditions are
// met:
//
//    * Redistributions of source code must retain the above copyright
// notice, this list of conditions and the following disclaimer.
//    * Redistributions in binary form must reproduce the above
// copyright notice, this list of conditions and the following disclaimer
// in the documentation and/or other materials provided with the
// distribution.
//    * Neither the name of Google Inc. nor the names of its
// contributors may be used to endorse or promote products derived from
// this software without specific prior written permission.
//
// THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
// "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
// LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
// A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
// OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
// SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
// LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
// DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
// THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
// (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
// OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
</pre></div>
