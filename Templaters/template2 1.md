
<%* 
  const filePath = tp.file.path(true);
  const folders = filePath.split('/');
  folders.pop();

  const getLastWord = (str) => { 
  const words = str.split(' '); 
  return words[words.length - 1]; 
  };

  const tags = folders.map(folder => '#' + folder).join(' ');
  const paths = folders.map(folder => '[[' + folder + ']]').join(' ');
  const lastPath = getLastWord(paths);

  const newFolder = tp.file.folder(true) + '/' + tp.file.title;

  tR += tags + ' ';
  tR += '#' + tp.date.now("YY-MM-DD") + '\n';
  tR += lastPath + ' ';
  await app.vault.createFolder(newFolder);
%>
