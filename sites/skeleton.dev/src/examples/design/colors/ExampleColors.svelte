<script lang="ts">
	const palette = [
		{
			name: 'Primary',
			ramp: [
				{
					value: 50,
					base: 'bg-primary-50',
					contrast: 'text-primary-contrast-50'
				},
				{
					value: 100,
					base: 'bg-primary-100',
					contrast: 'text-primary-contrast-100'
				},
				{
					value: 200,
					base: 'bg-primary-200',
					contrast: 'text-primary-contrast-200'
				},
				{
					value: 300,
					base: 'bg-primary-300',
					contrast: 'text-primary-contrast-300'
				},
				{
					value: 400,
					base: 'bg-primary-400',
					contrast: 'text-primary-contrast-400'
				},
				{
					value: 500,
					base: 'bg-primary-500',
					contrast: 'text-primary-contrast-500'
				},
				{
					value: 600,
					base: 'bg-primary-600',
					contrast: 'text-primary-contrast-600'
				},
				{
					value: 700,
					base: 'bg-primary-700',
					contrast: 'text-primary-contrast-700'
				},
				{
					value: 800,
					base: 'bg-primary-800',
					contrast: 'text-primary-contrast-800'
				},
				{
					value: 900,
					base: 'bg-primary-900',
					contrast: 'text-primary-contrast-900'
				},
				{
					value: 950,
					base: 'bg-primary-950',
					contrast: 'text-primary-contrast-950'
				}
			]
		},
		{
			name: 'Secondary',
			ramp: [
				{
					value: 50,
					base: 'bg-secondary-50',
					contrast: 'text-secondary-contrast-50'
				},
				{
					value: 100,
					base: 'bg-secondary-100',
					contrast: 'text-secondary-contrast-100'
				},
				{
					value: 200,
					base: 'bg-secondary-200',
					contrast: 'text-secondary-contrast-200'
				},
				{
					value: 300,
					base: 'bg-secondary-300',
					contrast: 'text-secondary-contrast-300'
				},
				{
					value: 400,
					base: 'bg-secondary-400',
					contrast: 'text-secondary-contrast-400'
				},
				{
					value: 500,
					base: 'bg-secondary-500',
					contrast: 'text-secondary-contrast-500'
				},
				{
					value: 600,
					base: 'bg-secondary-600',
					contrast: 'text-secondary-contrast-600'
				},
				{
					value: 700,
					base: 'bg-secondary-700',
					contrast: 'text-secondary-contrast-700'
				},
				{
					value: 800,
					base: 'bg-secondary-800',
					contrast: 'text-secondary-contrast-800'
				},
				{
					value: 900,
					base: 'bg-secondary-900',
					contrast: 'text-secondary-contrast-900'
				},
				{
					value: 950,
					base: 'bg-secondary-950',
					contrast: 'text-secondary-contrast-950'
				}
			]
		},
		{
			name: 'Tertiary',
			ramp: [
				{
					value: 50,
					base: 'bg-tertiary-50',
					contrast: 'text-tertiary-contrast-50'
				},
				{
					value: 100,
					base: 'bg-tertiary-100',
					contrast: 'text-tertiary-contrast-100'
				},
				{
					value: 200,
					base: 'bg-tertiary-200',
					contrast: 'text-tertiary-contrast-200'
				},
				{
					value: 300,
					base: 'bg-tertiary-300',
					contrast: 'text-tertiary-contrast-300'
				},
				{
					value: 400,
					base: 'bg-tertiary-400',
					contrast: 'text-tertiary-contrast-400'
				},
				{
					value: 500,
					base: 'bg-tertiary-500',
					contrast: 'text-tertiary-contrast-500'
				},
				{
					value: 600,
					base: 'bg-tertiary-600',
					contrast: 'text-tertiary-contrast-600'
				},
				{
					value: 700,
					base: 'bg-tertiary-700',
					contrast: 'text-tertiary-contrast-700'
				},
				{
					value: 800,
					base: 'bg-tertiary-800',
					contrast: 'text-tertiary-contrast-800'
				},
				{
					value: 900,
					base: 'bg-tertiary-900',
					contrast: 'text-tertiary-contrast-900'
				},
				{
					value: 950,
					base: 'bg-tertiary-950',
					contrast: 'text-tertiary-contrast-950'
				}
			]
		},
		{
			name: 'Success',
			ramp: [
				{
					value: 50,
					base: 'bg-success-50',
					contrast: 'text-success-contrast-50'
				},
				{
					value: 100,
					base: 'bg-success-100',
					contrast: 'text-success-contrast-100'
				},
				{
					value: 200,
					base: 'bg-success-200',
					contrast: 'text-success-contrast-200'
				},
				{
					value: 300,
					base: 'bg-success-300',
					contrast: 'text-success-contrast-300'
				},
				{
					value: 400,
					base: 'bg-success-400',
					contrast: 'text-success-contrast-400'
				},
				{
					value: 500,
					base: 'bg-success-500',
					contrast: 'text-success-contrast-500'
				},
				{
					value: 600,
					base: 'bg-success-600',
					contrast: 'text-success-contrast-600'
				},
				{
					value: 700,
					base: 'bg-success-700',
					contrast: 'text-success-contrast-700'
				},
				{
					value: 800,
					base: 'bg-success-800',
					contrast: 'text-success-contrast-800'
				},
				{
					value: 900,
					base: 'bg-success-900',
					contrast: 'text-success-contrast-900'
				},
				{
					value: 950,
					base: 'bg-success-950',
					contrast: 'text-success-contrast-950'
				}
			]
		},
		{
			name: 'Warning',
			ramp: [
				{
					value: 50,
					base: 'bg-warning-50',
					contrast: 'text-warning-contrast-50'
				},
				{
					value: 100,
					base: 'bg-warning-100',
					contrast: 'text-warning-contrast-100'
				},
				{
					value: 200,
					base: 'bg-warning-200',
					contrast: 'text-warning-contrast-200'
				},
				{
					value: 300,
					base: 'bg-warning-300',
					contrast: 'text-warning-contrast-300'
				},
				{
					value: 400,
					base: 'bg-warning-400',
					contrast: 'text-warning-contrast-400'
				},
				{
					value: 500,
					base: 'bg-warning-500',
					contrast: 'text-warning-contrast-500'
				},
				{
					value: 600,
					base: 'bg-warning-600',
					contrast: 'text-warning-contrast-600'
				},
				{
					value: 700,
					base: 'bg-warning-700',
					contrast: 'text-warning-contrast-700'
				},
				{
					value: 800,
					base: 'bg-warning-800',
					contrast: 'text-warning-contrast-800'
				},
				{
					value: 900,
					base: 'bg-warning-900',
					contrast: 'text-warning-contrast-900'
				},
				{
					value: 950,
					base: 'bg-warning-950',
					contrast: 'text-warning-contrast-950'
				}
			]
		},
		{
			name: 'Error',
			ramp: [
				{
					value: 50,
					base: 'bg-error-50',
					contrast: 'text-error-contrast-50'
				},
				{
					value: 100,
					base: 'bg-error-100',
					contrast: 'text-error-contrast-100'
				},
				{
					value: 200,
					base: 'bg-error-200',
					contrast: 'text-error-contrast-200'
				},
				{
					value: 300,
					base: 'bg-error-300',
					contrast: 'text-error-contrast-300'
				},
				{
					value: 400,
					base: 'bg-error-400',
					contrast: 'text-error-contrast-400'
				},
				{
					value: 500,
					base: 'bg-error-500',
					contrast: 'text-error-contrast-500'
				},
				{
					value: 600,
					base: 'bg-error-600',
					contrast: 'text-error-contrast-600'
				},
				{
					value: 700,
					base: 'bg-error-700',
					contrast: 'text-error-contrast-700'
				},
				{
					value: 800,
					base: 'bg-error-800',
					contrast: 'text-error-contrast-800'
				},
				{
					value: 900,
					base: 'bg-error-900',
					contrast: 'text-error-contrast-900'
				},
				{
					value: 950,
					base: 'bg-error-950',
					contrast: 'text-error-contrast-950'
				}
			]
		},
		{
			name: 'Surface',
			ramp: [
				{
					value: 50,
					base: 'bg-surface-50',
					contrast: 'text-surface-contrast-50'
				},
				{
					value: 100,
					base: 'bg-surface-100',
					contrast: 'text-surface-contrast-100'
				},
				{
					value: 200,
					base: 'bg-surface-200',
					contrast: 'text-surface-contrast-200'
				},
				{
					value: 300,
					base: 'bg-surface-300',
					contrast: 'text-surface-contrast-300'
				},
				{
					value: 400,
					base: 'bg-surface-400',
					contrast: 'text-surface-contrast-400'
				},
				{
					value: 500,
					base: 'bg-surface-500',
					contrast: 'text-surface-contrast-500'
				},
				{
					value: 600,
					base: 'bg-surface-600',
					contrast: 'text-surface-contrast-600'
				},
				{
					value: 700,
					base: 'bg-surface-700',
					contrast: 'text-surface-contrast-700'
				},
				{
					value: 800,
					base: 'bg-surface-800',
					contrast: 'text-surface-contrast-800'
				},
				{
					value: 900,
					base: 'bg-surface-900',
					contrast: 'text-surface-contrast-900'
				},
				{
					value: 950,
					base: 'bg-surface-950',
					contrast: 'text-surface-contrast-950'
				}
			]
		}
	];
</script>

<div class="grid w-full grid-cols-2 lg:grid-cols-7">
	{#each palette as color}
		<div class="space-y-4 text-center">
			<small class="block opacity-60">{color.name}</small>
			<div class="grid grid-rows-11">
				{#each color.ramp as shade}
					<div class="{shade.base} flex items-center justify-center py-2">
						<strong class={[shade.contrast, { underline: shade.value === 500 }, 'text-sm']}>{shade.value}</strong>
					</div>
				{/each}
			</div>
		</div>
	{/each}
</div>
