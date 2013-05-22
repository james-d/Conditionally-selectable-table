An implementation of TableSelectionModel that allows items in the table to be selectable or unselectable.
Table items must implement the Selectable interface, which simply provides access to a JavaFX BooleanProperty
indicating if the item is selectable or not. The selection model will deselect items that become unselectable; access to the Selectable's selctable property should only be made from the JavaFX Application Thread.
