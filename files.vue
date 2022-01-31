<script lang="js" frontend>
import FilesFactory from './libs/files-factory';

app.service('$files', function() {
	return FilesFactory();
});
</script>
