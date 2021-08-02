<template>
  <div>
		<el-result icon="error" title="use the 'sub-title'">
			<template #sub-title>
				This is the second level heading
			</template>
			<template #extra>
				<el-button type="primary" size="medium">返回</el-button>
			</template>
		</el-result>

		<el-result icon="success" title="use the 'subTitle'">
			<template #subTitle>
				This is the second level heading
			</template>
			<template #extra>
				<el-button type="primary" size="medium">返回</el-button>
			</template>
		</el-result>
	</div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>

</style>
