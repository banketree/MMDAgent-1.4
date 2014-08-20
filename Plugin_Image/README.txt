【ソフト名】  Plugin_Image.dll
【バージョン】0.1.1.0
【製作者】    CUBE370
【製作者HP】  http://cube370.blog87.fc2.com/
【公開日】    2014/03/18
【配布元】    http://cube370.blog87.fc2.com/
【専用wiki】  http://cube370.wiki.fc2.com/
【動作環境】  Windows 7
【ライセンス】BSDライセンス

―――――――――――――――――――――――――――――――――――――

■はじめに
  本プラグインはMMDAgent用です。
  MMDAgentの3次元空間に任意の画像を表示させることができます。
  画像形式はbmp、png、jpgに対応しています。

■動作環境
  64bit版 Windows 7 でのみ動作確認しています。

■対応状況
  MMDAgent-1.4

■インストール方法
  MMDAgentのPluginsフォルダにPlugin_Image.dllをコピーしてください。

■追加されるコマンド/イベント
  IMAGE_ADD|(alias)|(file name)|(size)|(position)|(rotation)|(face ON or OFF)
  IMAGE_CHANGE|(alias)|(file name)
  IMAGE_DELETE|(alias)
  IMAGE_EVENT_ADD|(alias)
  IMAGE_EVENT_CHANGE|(alias)
  IMAGE_EVENT_DELETE|(alias)

・各パラメータについて
  (alias)     : エイリアス
  (file name) : 表示したい画像のファイルパスを指定する
  (size)      : 表示する画像の大きさ。w,hで指定する。
  (position)  : 表示位置。x,y,zで指定する。
  (rotation)  : 回転。x,y,zで指定する。
  (face)      : 画像の裏面の描画指定。ONで描画。

■その他注意事項
  表示できる画像の数はそれぞれ最大128個です。
  不具合等はブログまたは@CUBE370までお願いします。

■更新履歴
  ver. 0.1.1.0 : MMDAgent-1.4準拠に変更。
  ver. 0.1.0.0 : とりあえず作ってみた。

■ライセンス

/* ----------------------------------------------------------------- */
/*           The Toolkit for Building Voice Interaction Systems      */
/*           "MMDAgent" developed by MMDAgent Project Team           */
/*           http://www.mmdagent.jp/                                 */
/* ----------------------------------------------------------------- */
/*                                                                   */
/*  Copyright (c) 2009-2013  Nagoya Institute of Technology          */
/*                           Department of Computer Science          */
/*                                                                   */
/* All rights reserved.                                              */
/*                                                                   */
/*  Copyright (c) 2012-2014  CUBE370                                 */
/*  All rights reserved.                                             */
/*                                                                   */
/* Redistribution and use in source and binary forms, with or        */
/* without modification, are permitted provided that the following   */
/* conditions are met:                                               */
/*                                                                   */
/* - Redistributions of source code must retain the above copyright  */
/*   notice, this list of conditions and the following disclaimer.   */
/* - Redistributions in binary form must reproduce the above         */
/*   copyright notice, this list of conditions and the following     */
/*   disclaimer in the documentation and/or other materials provided */
/*   with the distribution.                                          */
/* - Neither the name of the MMDAgent project team nor the names of  */
/*   its contributors may be used to endorse or promote products     */
/*   derived from this software without specific prior written       */
/*   permission.                                                     */
/*                                                                   */
/* THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND            */
/* CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES,       */
/* INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF          */
/* MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE          */
/* DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS */
/* BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,          */
/* EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED   */
/* TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,     */
/* DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON */
/* ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,   */
/* OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY    */
/* OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE           */
/* POSSIBILITY OF SUCH DAMAGE.                                       */
/* ----------------------------------------------------------------- */
