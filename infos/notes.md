# ANOTAÇÕES

## Teste do Parseador

```c
void	printmap(t_mdata *ms)
{
	int	i;
	int	j;
	
	i = 0;
	while (i < ms->col)
	{
		j = 0;
		{
			while (j < ms->row)
			{
				//if (ms->coord[i][j].color)
					printf("Col: %.0f | Row: %.0f | Z: %.0f | Color: %i\n", ms->coord[i][j].coord[0], ms->coord[i][j].coord[1], ms->coord[i][j].coord[2], ms->coord[i][j].color);
				j++;
			}
		}
		i++;
	}
}
```
