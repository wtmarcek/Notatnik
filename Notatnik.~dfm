object Form1: TForm1
  Left = 192
  Top = 125
  Width = 928
  Height = 480
  Caption = 'Form1'
  Color = clBtnFace
  Font.Charset = DEFAULT_CHARSET
  Font.Color = clWindowText
  Font.Height = -11
  Font.Name = 'MS Sans Serif'
  Font.Style = []
  Menu = MainMenu1
  OldCreateOrder = False
  OnClose = FormClose
  PixelsPerInch = 96
  TextHeight = 13
  object tresc: TMemo
    Left = 0
    Top = 0
    Width = 912
    Height = 421
    Align = alClient
    Lines.Strings = (
      '')
    ScrollBars = ssVertical
    TabOrder = 0
    OnKeyDown = trescKeyDown
  end
  object MainMenu1: TMainMenu
    Left = 824
    Top = 24
    object Plik1: TMenuItem
      Caption = '&Plik'
      object Nowy1: TMenuItem
        Caption = '&Nowy'
        OnClick = Nowy1Click
      end
      object Otwrz1: TMenuItem
        Caption = '&Otw'#243'rz'
        OnClick = Otwrz1Click
      end
      object Zapisz1: TMenuItem
        Caption = '&Zapisz'
        OnClick = Zapisz1Click
      end
      object Zapiszjako1: TMenuItem
        Caption = '&Zapisz jako'
        OnClick = Zapiszjako1Click
      end
      object N1: TMenuItem
        Caption = '-'
      end
      object N2: TMenuItem
        Caption = '-'
      end
      object Zakocz1: TMenuItem
        Caption = '&Zako'#324'cz'
        OnClick = Zakocz1Click
      end
    end
    object Edycja1: TMenuItem
      Caption = '&Edycja'
      object WytnijCtrlX1: TMenuItem
        Caption = '&Wytnij    Ctrl+X'
        OnClick = WytnijCtrlX1Click
      end
      object KopiujCtrlC1: TMenuItem
        Caption = '&Kopiuj    Ctrl+C'
        OnClick = KopiujCtrlC1Click
      end
      object WklejCtrlV1: TMenuItem
        Caption = '&Wklej     Ctrl+V'
        OnClick = WklejCtrlV1Click
      end
    end
    object Format1: TMenuItem
      Caption = '&Format'
      object Zawijaniewierszy1: TMenuItem
        Caption = 'Zawijanie wierszy'
        OnClick = Zawijaniewierszy1Click
      end
      object Czcionka1: TMenuItem
        Caption = 'Czcionka'
      end
    end
    object Pomoc1: TMenuItem
      Caption = '&Pomoc'
      object Informacja1: TMenuItem
        Caption = '&Informacja'
        object Oprogramie1: TMenuItem
          Caption = 'O programie'
        end
        object Zapraszamnabloga1: TMenuItem
          Caption = 'Zapraszam na bloga'
        end
      end
    end
  end
  object OpenDialog1: TOpenDialog
    Filter = 'Pliki tekstowe|*.txt|Wszytkie pliki|*.*'
    Left = 792
    Top = 24
  end
  object SaveDialog1: TSaveDialog
    Filter = 'Plik tekstowy [TXT]|*.txt|Wszystkie pliki|*.*'
    Options = [ofOverwritePrompt, ofHideReadOnly, ofEnableSizing]
    Left = 760
    Top = 24
  end
end
