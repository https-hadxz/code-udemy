using Godot;
using System;

public partial class print : Control
{
	// Called when the node enters the scene tree for the first time.
	public override void _Ready()
	{
        GD.Print("Hello World");
    }
}
