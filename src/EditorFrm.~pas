unit EditorFrm;

interface

uses 
  Windows, Messages, SysUtils, Classes, Forms, DAVDCommon, DVSTModule,
  Controls, ExtCtrls, cDIBPanel, cDIBImageList, cDIBKnob, cDIBControl,
  cDIBImage;

type
  TEditorForm = class(TForm)
    Skin: TDIBImageList;
    Kontainer: TDIBContainer;
    DIBImage1: TDIBImage;
    Knob: TDIBImageList;
    DIBKnob1: TDIBKnob;
    DIBKnob2: TDIBKnob;
    procedure DIBKnob1Change(Sender: TObject);
    procedure DIBKnob2Change(Sender: TObject);
  end;

implementation

{$R *.DFM}

procedure TEditorForm.DIBKnob1Change(Sender: TObject);
begin
DIBKnob1.IndexMain.DIBIndex := DIBKnob1.Position;
end;

procedure TEditorForm.DIBKnob2Change(Sender: TObject);
begin

DIBKnob2.IndexMain.DIBIndex := DIBKnob2.Position;
end;

end.