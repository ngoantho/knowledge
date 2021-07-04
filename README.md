This is an ongoing project to digitize, organize, and expand all of my notes covering topics in computer science and more.

## Indices
This wiki is organized around a hierarchy of indices and sub-indices of interconnected topics. The top level indices are listed below.
[Appreciation of Art (index)](Appreciation%20of%20Art/Appreciation%20of%20Art%20(index).md)

## Vault Workflow
```mermaid
graph TD

subgraph Zettelkasten
	daily(daily note)
	literature(literature note)
	permanent(permanent note)
	index(index note aka MOC)
	topic(topic note)

	daily-->literature
	literature-->permanent
	permanent-->index
	permanent-->topic-->index
end

moc(MOC)
page(Page)
topic2(Topic)

moc --> page
moc --> topic2 --> page
```